# v1.1.0

This is the first release of the forked version!

* Add `enableMove`: allows you to disable the check for moving a window.<br>
  This is useful for people that want to use the macOS-builtin cmd-ctrl-drag behaviour
  you can use by running `defaults write -g NSWindowShouldDragOnGesture YES`

* Add support for using any mouse button (thanks, @cdump!)

* Add resizing from any corner (thanks, @gjbadros!)

* Fix dragging full-screen windows incorrectly showing the moving/resizing ghost

* Fix deprecation warning

* Fix incorrect ghost corner radius on modern macOS

# v1.0.2

* When moving a window, we now move a transparent `hs.canvas` so it feels fast.

# v1.0.1

* Add `disabledApps` configuration option

# v1.0.0

* First release!
