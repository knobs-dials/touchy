# touchy

I wanted a way to visualize musical intervals, in a layout that's not a keyboard (because they're effectively biased to specific modes/keys).

This is an experiment written for [Kivy](https://kivy.org/), because it's very convenient for this sort of thing.


It
- allows varied layout. So far I've played with 
  - a few octaves of chromatic (see screenshot)
  - guitar layout
  - isometric with thirds and fifths
- optionally mentions
  - note name (off in screenshot below)
  - Intervals to all touched notes
- colors by consonance (blue) or dissonance (red)
- reacts to multitouch
- reacts to MIDI input
- plays to MIDI

![Animated screenshot of playing a major triad](/screenshot.gif?raw=true)


# Requirements
- [Kivy](https://kivy.org/doc/stable/gettingstarted/installation.html)


# TODO
- make it react to sliding touch
- change button behaviour, right now reacts twice
- figure out whether it's changing text that makes it slow to respond to lots of touches at once
- figure out other realtimeish issues
- put code here in repository
- add on-screen swapping to other layouts, switching midi channel, what to show
- add file config (e.g. for what MIDI device name to prefer)

