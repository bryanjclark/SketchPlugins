SketchPlugins
=============

A git repo containing various plugins for [Sketch](http://bohemiancoding.com/sketch/).

- - -

### Align
Allows you to align layers inside another layer. This doesn't move the bottom selected layer, and is a better implementation I believe that how Sketch handles this currently (where they average the position of all selected layers).

* __Both in Selection__ (cmd option control x): aligns selected layers vertically and horizontally to the bottom most selected layer
* __Horizontally in Selection__ (cmd option control h): aligns selected layers horizontally to the bottom most selected layer
* __Vertically in Selection__ (cmd option control v): aligns selected layers vertically to the bottom most selected layer

### Save Page to PNG
Hit (Command + Option + Control + E) to save your entire page to a single PNG, in the same directory as your sketch file. This is super useful if you want to show all of your artboards at once.

### Handy
![Handy](https://dl.dropboxusercontent.com/u/144234624/Sketch/handy.png)

Handy is a plugin that makes working with guides easier in Sketch. It includes two plugins currently:
* __Add Guide__ (cmd shift option g): lets you add a vertical or horizontal guide at any point, for example 'v,100' adds a vertical guide at 100px. You can also pass multiple, space-separated values ('v,100 h,200').
* __Remove Guides__ (cmd shift option r): removes all guides across your artboards.

Note you need Rulers turned on (Control R) to see guides 
