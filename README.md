## luxaritas/reaper-config

This repository includes various notes, configurations, templates, and custom utilities for my
personal REAPER setup (both for my own records and in case someone else finds it useful!).

## Theme
[Hydra - iZ](https://stash.reaper.fm/theme/2446/Hydra%20-%20iZ%20v1.3)

## Extensions
[ReaPack](https://reapack.com/)
[SWS](https://www.sws-extension.org/)
[Reaticulate](https://reaticulate.com/)
[js_ReaScriptAPI](https://forum.cockos.com/showthread.php?t=212174) (for Reaticulate)

## Cycle Actions
[SWS/S&M_Cycleactions.ini] contains my collection of shortcuts built with the SWS/S&M extension's
cycle action feature. This file can be imported via the cycle action editor.
- Toggle Selected FX Offline + Lock: Handy for when you want to quickly enable/disable VSTs on
  some tracks to save resources (particularly when offlining FX by default in a template),
  and have a visual indicator that it is indeed disabled.

## SWS Colors
[SWS/Colors] contains color pallets built with the SWS/S&M extension's track color management.
These can be imported via the color management dialog.
- main: Primary color profile used to correspond to different instrument sections.
    - Blue: Woodwinds
    - Yellow: Brass
    - Green: Keys
    - Orange: Percussion
    - Purple: Vox
    - Red: Strings
    - Magenta: Synths

## MenuSets
[MenuSets] contains my custom menu layouts. These can be imported in the customize menus/toolbars dialog.
- MainToolbar: Added offline and lock shortcut to the main toolbar

## Toolbar Icons
[ToolbarIcons] contains icons I've created for my custom toolbars. This is laid out just like
the Data/toolbar_icons directory in the REAPER resource path (including rendered icons at all resolutions),
except for the addition of the source directory which contains the source SVG files.
