# vf-audio-reactive
Tried to make this sort of intuitive
The three sliders change the axes of the font selected (if only one axes present it's just the first slider)
if you hit play on the audio file you can see some audio reactivity working
currently just set to bass => axis 1
can do a lot with the setup variables of the analyser and the analyseAudio function
in the analyseAudio function a lot of changeRootVar() are commented - only have one uncommented at a time but you can switch them out to see different effects
if you want to change audio file drag a new file into the folder and change the src attribute on line 45 of index.html