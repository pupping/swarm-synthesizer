# swarm-synthesizer
multichannel granular synthesis &amp; audio spatialization software

	first, from the bottom of my heart, thank you so much for your support. you have helped provide life-saving aid to Palestinians in this time of crisis. i cannot overstate how grateful i am for your help.

	Swarm is a granular synthesis and spatial audio workstation made using Max and IRCAM Spat5. below is a pretty thorough guide to getting the most out of it. of course, you can ignore this and just experiment! thanks for playing with it. i hope you like it!

	using the input module, you can choose an audio source to work with. there are a variety of simple oscillators, an ADC (microphone or external audio input), a sound file player, filtered noise sources, a custom waveform designer, and a click designer. you can switch between sources using the source dropdown menu. they are all very fun, but i have the most fun using the ADC. you can hear the unprocessed sound live by pressing the bypass button at the bottom of the granular synthesizer module. 

	the granular synthesizer module is constantly recording into a looping buffer. by adjusting the looping buffer length slider, you can determine how much long a loop will record before old sounds are overwritten by new ones. to stop recording new sounds and loop the old ones infinitely, press the freeze button, or just hit “F” on your keyboard. clear the buffer and erase all sounds by hitting the clear button or pressing “C” on your keyboard. 
	sounds that are recorded into the granular synthesizer are sliced into 24 unique, transient bits of sound called grains. the duration, amplitude, sample location, playback speed/direction, and filtering of each grain is independently modulated based on the settings of the various var dials. set them to zero if you don’t want them to be modulated, or crank them from -200 - 200% for varying degrees of randomness. you can also modulate these settings in a more consistent way, using the respective effect dials without the var suffix. i won’t describe them all, but i find the speed knob to be the most fun. there are also global parameters, like room presence, which influences reverb behavior, and drop, which influences the simulation of distance.

	the 24 unique grains of audio are all sent to the final output filter module for filtering. you can change the filter type using the dropdown menu, and influence the filter parameters by clicking and dragging it, or turning the cutoff and resonance dials.

	the spatializer module takes the 24 grains and distributes them throughout simulated 3-dimensional space as independent sound-objects. these sound objects fly around in a chaotic way that mimics the behavior of a flock of birds (thanks to Craig Reynolds’ Boid Algorithm). influence the behavior of the flock using the various number boxes. the coolest one is definitely the willingness to change speed and direction setting. crank it up to twenty and then drop it down to 4 and watch them fly around using the viewer. 	the viewer is really cool. it allows you to watch your sound objects fly around. turn it on using the open button, and make it stay at the front of the screen using the floating switch. the same logic applies to the oper section, where you can influence the sound qualities of individual objects, or the qualities of the simulated room (via the R1 tab in the oper window).
	now that you can see your little sound objects, zoom in and out by scrolling. you can also tell them where to go by using the attractor object. click and drag the attractor and watch the objects flock to it. the z option makes them move vertically, which makes them quieter (since they would be flying above your head, and thus, farther from your ears). listen to the sound objects zoom from left to right. it is really effective on good speakers or headphones. also, if you have access to 4 speakers, reach out to me and i’ll send you a quadraphonic version.

	finally, you can record your creations using the recorder module. first, open a file to record into, and then simply hit record. now you’re a musician/sound designer!

	i hope this helps you have fun! i hope you enjoy! thank you so much for playing with my instrument. reach out to me at d09913@protonmail.com if you have any questions or feedback please. 

	free Palestine! peace! -emad
