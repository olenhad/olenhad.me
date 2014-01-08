---
layout: page
permalink: /projects/index.html
title: Projects
modified: 9-9-2013
image:
  feature: texture-feature-02.jpg
  credit: Texture Lovers
  creditlink: http://texturelovers.com
---


## Eyrie

<img src="/images/thrust-sample.png">

<br>

Eyrie is a tool that generates flight visualizations in KML from black box data. I developed eyrie as my final year project at NUS for the Air Accident Investigation Board (AAIB) in Singapore. 

It is fully implemented in Clojure.


## [(arc)](https://github.com/BenTobias/arc)

_(def arc '(arc reads code))_

<br>

<img src="/images/arc.png">

<br>

Arc is code-reader for the iPad, designed to work on iOS6 and above. It's features include:

* Syntax Highlighting
* Code Folding
* Compatibility with Textmate Bundles and Themes
* Multiple document sources (including Dropbox, Google Drive and Skydrive)
* Plugin based architecture

My primary contributions to the project were the syntax highlighting and code folding plugins. For syntax highlighting, I initially tried working with Textmate's parser, but due to dependency issues, ended up developing my own from scratch. The chief complexity was ensuring compatibility with textmate grammars, as we wanted plug and play compatibility with existing Textmate bundles and themes.

Code folding was also based on patterns specified in Textmate bundles, and implemented using interval trees.

The project is [open source](https://github.com/BenTobias/arc) and MIT Licensed

## [Hush](http://hush.sh)

<img src="/images/hush.png">

<br>

Hush is a realtime anonymous social platform my team designed for [CS3216](http://www.comp.nus.edu.sg/~cs3216/). It was built on nodejs using [express](http://expressjs.com/) with mongodb for persistence, redis for sessions and elastic search. The code is open sourced and available [here](https://github.com/darora/hush)

## [Newton](https://github.com/olenhad/Newton)

Newton is a simple 2d Physics engine, developed in Objective C for iOS. It was built more as a learning exercise than anything else, so it's not very performant. It currently only supports rectangle based polygons.




