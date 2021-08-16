# OSC-M4L-Patches
Custom M4L devices for sending OSC values to MaxMSP.

These are modifed patches based on Ableton stock M4L devices, as well the OSCBuddy patch from TomCosm.
If you have the need for sending note or loudness data out of Ableton, especially for audio-reactivity inside of MaxMSP (or any program
that accepts OSC data), these can be useful. 

If you are unfamiliar with how OSC data works, I recommend using the stock devices and seeking the relevant documentation for those. They work
in the same way.

-OSCMidiSend3000 is exactly like the stock one, but it saves the port value when you close the ableton project. 
If you have a lot of tracks this can be really useful, otherwise you will have to retype port numbers every time you relaunch Ableton.
A small change, but useful for me.
Original: https://github.com/Ableton/m4l-connection-kit/tree/master/OSC%20MIDI%20Send

-LFO3000 is a modified version of the stock LFO, except you can map to other properties and send the LFO signal as an OSC value.

-OSCAmplitudeSend3000 sends the amplitude (loudness) value in a specified range of numbers.
This patch borrows from the OSCBuddy patch by TomCosm, which I recommend checking out.

Youtube Demo:

https://www.youtube.com/watch?v=ASPzjJ5OYoU&ab_channel=TomCosm

Link to download:

https://tomcosm.gumroad.com/l/UCvKN

The problem is that as far as I know there can only be one OSCBuddy device used in a project at a time, and only 4 tracks are supported. 
My device just sends the amplitude signal value, and you can drag the device onto as many tracks as you want. 
