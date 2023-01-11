# XWACOMCONFIG
- xwacomconfig - auto configurator of the Wacom tablet.
- Map the tablet to fit the clicked window.

## REQUIREMENTS
- xinput
- xsetwacom
- xdpyinfo
- xdotool
- python-xlib

## USAGE
- `./xwacomconfig`: non track mode, map the tablet to the clicked window only once
- `./xwacomconfig track`: trackmode, automatically remap the tablet according to the clicked window movement and resizing.

## SPECIFICATIONS
- The aspect ratio of the area to which the tablet is mapped is equal to that of the physical world of the tablet.
- If the window and tablet have different aspect ratios, map the top/bottom or left/right edges of the window to correspond to the tablet edges.

## SEE ALSO
- [hogedraw](https://github.com/void-hoge/hogedraw)

## AUTHOR
- Mugi Noda(void-hoge)
