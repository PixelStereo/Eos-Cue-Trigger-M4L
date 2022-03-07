# Eos-Cue-Trigger-M4L

This is a Max4Live device that will send an OSC message to an EOS lighting software.
It will trig a cue on a selected cuelist from a midi noteon

#1 Drag the device in a midi track.   
#2 Create a midi clip.   
#3 Rename the clip with the name of the cuelist and the cue you want to trigger, separeted with a dash (-) e.g. : 2-33 will trig the cue 23 of the cuelist 2.   
#4 If you want to trig several cues in a clip, just separate each message with a space, and create several note on in the clip. e.g. : 2-33 3-44.   

The note does not matter.

You can also address a submaster, just add S before. e.g. : S14 will trig the submaster at full at note on, and cut it down at note off.
