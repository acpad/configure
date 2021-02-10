# WebMIDI device configuration tool

A simple configuration tool for small MIDI devices. It runs in the web browser on a desktop or mobile phone without the need to download or install any other software. It is suited for devices which do not have a network connection themselves.

The Web browser connects over [webMIDI](https://webaudio.github.io/web-midi-api/#extensions-to-the-navigator-interface) to the MIDI device. The messages between the browser and the device are [MIDI System Exclusive](https://en.wikipedia.org/wiki/MIDI#System_Exclusive_messages) messages.
