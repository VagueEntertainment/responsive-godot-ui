# responsive-godot-ui
Helper scripts to add simple responsive design to Godot

This may be discontinued depending on how well Godot 4 handles UI elements, and largely based on issues that have been worked around in the passed. 

Current issues to be addressed.

* Font resizing based on resolution of screen or window (most likely window)
* UI element animations that are based on cords. 
* automatically replace ui elements with more suitable ones based on window size.

General concept.

Simple gdscript implementation

```gdscript

_process(delta)
  Responsive(node,window)

```

