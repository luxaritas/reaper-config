## luxaritas/reaper-config

This repository includes various notes, configurations, templates, and custom utilities for my
personal REAPER setup (both for my own records and in case someone else finds it useful!).

## Theme
[Hydra - iZ](https://stash.reaper.fm/theme/2446/Hydra%20-%20iZ%20v1.3)

## Extensions
- [ReaPack](https://reapack.com/)
- [SWS](https://www.sws-extension.org/)
- [Reaticulate](https://reaticulate.com/)
- [js_ReaScriptAPI](https://forum.cockos.com/showthread.php?t=212174) (for Reaticulate)

## Project Templates
[ProjectTemplates](./ProjectTemplates) contains my templates I use when starting up a new project so
that have instruments pre-loaded, articulation maps configured, routing and stemming handled, etc.
- [Main.RPP](./ProjectTemplates/Main.RPP): My primary composing template. The setup takes inspiration from
  [Trevor Morris](https://www.youtube.com/watch?v=on0xJBTtMbI) and [Christian Henson](https://www.youtube.com/watch?v=Cyh10tOuIKc)
  among others. Its organization includes woodwinds, brass, strings, percussion, keys, voice, and synths.
  There is a set of mix stems (doing some rough grouping, splitting out shorts vs longs, etc),
  delivery stems (which are much less in number), and an FX bus for each delivery stem for reverb
  (which is routed to the delivery stems, but can easily be disabled). Currently this template centers largely
  around BBCSO core, though I've slotted in a couple of other libraries which I've acquired over time.
  All VSTs are offlined on loading the template (easy on CPU/RAM and fast to boot), and it's designed
  to be able to easily slot in other libraries with minimal need for additional setup for routing, etc.
- [Reaticulate.reabank](./ProjectTemplates/Reaticulate.reabank): The Reaticulate articulation map used for my template.
  Some contents are pulled from existing Reaticulate banks, but are customized to work with how the template is structured.

## Cycle Actions
[SWS/S&M_Cycleactions.ini](./SWS/S&M_Cycleactions.ini) contains my collection of shortcuts built with
the SWS/S&M extension's cycle action feature. This file can be imported via the cycle action editor.
- Toggle Selected FX Offline + Lock: Handy for when you want to quickly enable/disable VSTs on
  some tracks to save resources (particularly when offlining FX by default in a template),
  and have a visual indicator that it is indeed disabled.

## SWS Colors
[SWS/Main.SWSColor](./SWS/Main.SWSColor) contains my primary color pallet corresponding to different instrument sections,
built with the SWS/S&M extension's track color management. This can be imported via the color management dialog.
  - Blue: Woodwinds
  - Yellow: Brass
  - Green: Keys
  - Orange: Percussion
  - Purple: Vox
  - Red: Strings
  - Magenta: Synths

## MenuSets
[MenuSets](./MenuSets) contains my custom menu layouts. These can be imported in the customize menus/toolbars dialog.
- MainToolbar: Added offline and lock shortcut to the main toolbar

## Toolbar Icons
[ToolbarIcons](./ToolbarIcons) contains icons I've created for my custom toolbars. This is laid out just like
the Data/toolbar_icons directory in the REAPER resource path (including rendered icons at all resolutions),
except for the addition of the source directory which contains the source SVG files.
