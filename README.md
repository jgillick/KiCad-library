# Jeremy's KiCad Library
Just a repository of custom KiCad symbols, footprints, and 3D modes I've created.

## General Setup

Download the library into a sensible place for user KiCad libraries (i.e `Documents/kicad/jgillick_libs`):

```bash
git clone https://github.com/jgillick/KiCad-library.git jgillick_libs
```

Then define a KiCad path variable to this directory
* KiCad App > Preferences > Configure Paths...
* Click "+"
* Enter:
  * Name: `JGILLICK_LIBS`
  * Path: `<Path to cloned directory>` (i.e. `~/Documents/kicad/jgillick_libs`)

## Add Libraries

Now add the various libraries you need:

* Either
  * KiCad App > Preferences > Manage Footprint Libraries...
  * KiCad App > Preferences > Manage Symbol Libraries...
* Click "+"
* Enter a nickname (i.e. `JGillick Button/Switch`)
* Enter a path to the library you want to add. (i.e. `${JGILLICK_LIBS}/footprints/Button_Switch.pretty`)