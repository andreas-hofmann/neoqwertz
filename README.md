# neoqwertz
If the NEO and QWERTZ layouts had a bastard child, this would be it.

This keyboard layout is basically a regular QWERTZ layout, but has layers 3-6 of the NEO2 layout added.
I created it because I don't want to be incredibly slow at work while getting adapted to a new keyboard layout,
but still want to enjoy the added benefit of the additional layers which NEO provides.

Checkout the description for the advanced layers at http://neo-layout.org

Load the layout like so:

    xkbcomp neoqwertz.xkb $DISPLAY &> /dev/null

Or add it globally in the X-server:

    sudo cp -r xkb /usr/share/X11
    setxkbmap de neoqwertz

Currently only support for X available. If you think this is cool and add
configs for Windows or any other OS, feel free to send me a pull request.
