The Dim Sum Labs door is stoney faced and it is hard to hear his
instructions.

We want to make people looking at the door be able to have a more
enjoyable experience, by giving them instructions and feedback.

This repository contains an Android app that can be installed on an old
and cheap tablet to make it open a URL on bootup in fullscreen mode.
When connected to the rest of the system, this URL is presenting the
realtime information from the door controller.  The tablet can then
be mounted outside the door to show information to visitors.

`adb shell` into the Dim Sum Labs door device and `echo` the door lock
URL into the **/nand/door** file.