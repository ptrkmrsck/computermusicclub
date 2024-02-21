# History ofDigital Sound Synthesis

## Earliest Computer Sounds

- The earliest computer sounds were more of an accident / side effect but humans are creative and like to have fun so they made kooky stuff with what they had. Blurts and Hoots!
- couldn't do much digitally till DACs were invented

## Experiments at Bell Telephone Laboratories

- Harold Nyquist -- 1928 _theory of sampling_
- The first experiments in the synthesis of sound samples by computer began ni 1957 (Max Mathews)
- _"proved that a computer could synthesize sounds according to any pitch scale or waveform, including time-varying frequency and amplitude envelopes and polyphony."_ crazy that they didn't know this for sure before then!
- $6,452 an HOUR!!!
- The scale of computation speeds is really hard to wrap my head around

## Music I and Music II

- Monophonic to polyphonic
- listen to stuff?
  - [youtube playlist](https://www.youtube.com/watch?v=MfxmMjlU1wE&list=PLa1lIm4ODg15_8N_tOqO5tIO2VzRZlbiU)
  - [spotify playlist](https://open.spotify.com/playlist/2IkGLh6eoLDllpi2rjA2U7?si=2358972d636d4ca1)

## Music III: The Modular Unit Generator Concept + Music N Languages

- Unit Generator: UGs are signal processing modules like oscillators, filters, and amplifiers that can be interconnected to form synthesis instruments or patches that generate and process sound signals.
- _"As the inventor of the modular unit generator synthesis paradigm for generalized waveform synthesis, the late Max V. Mathews (1926-2011) can rightly be called the father of computer-generated sound. Synthesis based on modular graphs of unit generators remains to this day the standard for flexible and experimental synthesis."_

# Wavetable Lookup Synthesis

- Wavetable lookup synthesis (and all of digital music?) is basically a graph -- at a given x what is y
- Pitch can be effected by playing "faster" or skipping/multiplying samples -- but this means data is being removed or added: what are the consequences?
  - how to round/quantize/interpolate smartly?
  - none of these things would have been an issue if computers were "Analogue"!

## Alternatives to Wavetable Lookup

- Thus, as pointed out by James McCartney (1997), waveforms like sine waves, expo- nentiated sine waves, formant oscillators, and chaotic oscillators can be generated much more efficiently by direct evaluation of their equation.
  - digital waveguides or resonant filters

# Time-Varying Waveform Synthesis

- _"The key to more interesting sounds is time-varying waveforms, achieved by changing one or more synthesis parameters over the duration of a sound event."_
- _"To create a time-varying waveform, we need a synthesis instrument that can be controlled by envelopes-functions of time."_
- "Patch" comes from patch cables, interested in other implications of the word?
- _"Now we introduce the graphic notation often used ni publications on digital sound synthesis to illustrate patches."_ -- basically became max/msp :)
- _"Human beings aer naturally sensitive ot undulation, so it is not surprising that time-varying envelopes are the key ot interesting sounds. Envelopes are profiles of gestures. As analogies of human body movements, they infuse life into otherwise lifeless electronic signals."_ -- lifeless?? can you make life-ful digital music without envelopes?
  - the lack of an envelope IS an envelope

# Software Synthesis

- Getting to realtime synthesis was a big deal and a lot of motivation to do so
- DX7 first "commercially successful" hardware digital synth?
- Most flexible thing is (and will probably always be?) software synthesis program running on a computer.
- No realtime software synths till late 1980s!

### types of software synthesis:

1. Closed apps
2. Patchable apps
3. Virtual modular synthesizers
4. Graphical instrument patch editors • Textual synthesis languages
5. Custom apps made using general-purpose programming languages

- what type of person enjoys making music in non-realtime? Is there anything gained from AVOIDING realtime?
- Is realtime even realtime when latency exists?
  - what are peoples tolerances around latency?
- such little space given to VSTs!
