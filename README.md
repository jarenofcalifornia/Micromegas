# MicroMegas Info
Micromegas is a granular sampler and looper, made for live performance. <br>
It can record and overdub live-audio in any speed or direction. It can overdub over any part of an original recording. <br>
It can play back these samples as a powerful looper, and/or as a polyphonic granular synthesizer. <br>
These two modes are interrelated, and can be synced together. <br>
The looper has quasi-granular parameters, and the granular synthesizer can act as a time-pitch independent looper. <br>
Micromegas is a Max for Live audio device, and works in Ableton. <br>
Place MicroMegas in an audio track, and place the included "Micromegas MIDI Sender" in a MIDI track. <br>

I've made two versions of MicroMegas. <br>
----"MicroMegas with SoftStep" contains code that allows the Softstep footpedal to control the parameters in powerful ways.
To send MIDI from the Softstep to MicroMegas, make sure your SoftStep Advanced Editor is open, place the included "Softstep MIDI Sender" in a MIDI track, and set this MIDI track to send/receive from SSCOM (Port 1). <br>
----"MicroMegas" is without SoftStep control, and thus has a couple extra GUI elements.


Bugs:

----Sometimes the karma~ object does not initialize, and one must open the patch and reinitialize the object. <br>
----Sometimes a MIDI note does not properly release. Workaround: trigger a number of voices greater than the max setting in the "Voice" param.

Micromegas is based on by Robert Henke's Granualtor II synthesizer, and Robert Constazo and Raja's karma~ live-sampler. Both were released for free. Thanks guys.
