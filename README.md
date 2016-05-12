# ember-electron-material-demo
Step-by-step, from scratch example of how to create a cross-platform, HTML5-based application

### Last updated: 5/12/2016

## Motivation
Ever since about 2012 (perhaps "the year of the JavaScript MVC frameworks") I have wanted to learn Ember.js, but attempting to do this in my free time always resulted in failure to get past the initial learning barrier.
Thankfully, I am now in a position where I am working on an ember-based project and can put time into learning it. 
In order to improve my own understanding and get some extra practice, I have decided to create this repository ([jacobq/ember-electron-material-demo](https://github.com/jacobq/ember-electron-material-demo)).
Perhaps it may also benefit you / the community,
(sometimes it is surprising how little missing steps or details can make it much harder to learn something than it ought to be)
so here it is.

## Install JS development tools

While this is intended to be "from scratch" there are good tutorials for some of these steps already.
Therefore I am going to mention them only briefly. Furthermore I assume you have full/privileged access
to a modern computer with a mainstream operating system
(I am using Debian Linux, but Windows 7/8/10 and Mac OS 10.8+ should work as well).

1. Install [git](https://git-scm.com/).
   If you are not already familiar with this source code management / revision control system then I strongly recommend
   taking a few minutes to get acquainted with it first. There are many good tutorials and training resources, such as 
   [the one on the git website](https://try.github.io/levels/1/challenges/1).
2. Install [Node.js](https://nodejs.org/en/download/current/). 
   This is "JavaScript freed from the confines of of web browsers" and able to be used for developing full-fledged programs.
   (e.g. while web browsers disallow access to the file system, network, etc. node provides APIs for these.)
3. *Optional:* Install an IDE such as
   [atom](https://atom.io/),
   [Visual Studio Code](https://code.visualstudio.com/),
   or
   [WebStorm](https://www.jetbrains.com/webstorm/download/)


## Install `npm` packages for ember

