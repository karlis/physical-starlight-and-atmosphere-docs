Presets allow to store a snapshot of your customized atmosphere settings and return to it later
or use already predefined presets provided by the addon.

!!! info
    Presets are introduced in v1.3.0. Till then default values were the current values of _Earth_ preset.


## Good to know
* `azimuth` and `elevation` properties are not stored in the preset.
* There are 2 presets offered by addon - _Earth_ & _Mars_
    * These are prefixed by `·` _(e.g. · Mars)_ and always located at the bottom of the preset list.
    * If deleted, after re-enabling the addon they will be available again.
* Whenever Blender is newly loaded Earth is set as a default world (even if saved
file has been loaded).


## Resetting to defaults
Resetting sets properties to _selected preset_ default values. In case when no preset is selected,
the value will be set to the `Earth` default value. 

### How to reset?
* To _reset single property_, hover on it and press ++backspace++ (Blender default behavior)
* To _reset section_ of properties to their defaults, click on the `reset` button in the bottom right corner
of the property set.
