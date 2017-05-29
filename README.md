Fork of https://github.com/plattysoft/Leonids

## Applied changes:

* update of minSdkVersion, targetSdkVersion and other versions to match app's ones
* cleanup of library manifest to prevent collisions with app's one
* patch from https://github.com/plattysoft/Leonids/issues/63
* support for multiple particle drawables per system
* reordering of the drawing view to draw particles on 'background'
* skipping of drawing view invalidate calls during particles fast-forwarding