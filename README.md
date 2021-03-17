# touchy

I wanted a way to visualize musical intervals, in a layout that's not a keyboard (because they're effectively biased to specific modes/keys).

This is an experiment written for [Kivy](https://kivy.org/), because it's very convenient for this sort of thing.


It 
- allows different layouts (I've played with chromatic, guitar layout, isometric with thirds and fifths)
- colors by consonance (blue) or dissonance (red)
- reacts to multitouch
- reacts to MIDI input
- plays to MIDI

![Animated screenshot of playing a major triad](/screenshot.gif?raw=true)


# Requirements
- [Kivy](https://kivy.org/doc/stable/gettingstarted/installation.html)


# TODO
- change button behaviour, right now reacts twice
- figure out whether that's the reason it is slow to respond to lots of touches at once
- put code here in repository
- add on-screen swapping to other layouts, switching midi channel, and other such config
- add file config (e.g. for what MIDI device name to prefer)

