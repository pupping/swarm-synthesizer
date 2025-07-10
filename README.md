Swarm is a realtime granular synthesis & audio spatialization environment made in Max with Spat5. (Currently only MacOS compatible)

- Record sound into a looping buffer. You can keep recording and overwriting old sounds, or freeze sounds in time. Sound sources include sample playback, filtered noise, simple oscillators, custom drawn waveforms, custom drawn impulses, or live external audio.


- Incoming audio is sliced into 24 individual grains that are each manipulated independently. Parameters like playback speed, start point, filtering, and playback direction could be modulated manually or randomly.

- Each grain is assigned to an independent object that moves around space as an individual in a group. They are distributed throughout simulated space using a "boid algorithm," designed to replicate the behavior of a flock of birds moving together. They consult their neighbors, match each other’s speeds, and flock around a common point of attraction. Manually program the flock to change their behaviors and move the attractor to guide them in a direction.

- Sounds output from the granular synthesizer can be filtered as a group before spatialization.

- Characteristics of the simulated space including room size and reverberance can be manually programmed.

Make sure to use an appropriate audio output source for your corresponding version!

email d09913@protonmail.com with questions.
