## 4 Voice Analog Drum Synthesizer

### [SCHEMATIC](X)

### Features:
#### 4 independent drum voices
- SN76477 arcade sound generator as the heart of each voice
- wide range VCO with sine, triangle, fixed pulse, and PWM pulse waveforms
- digital swept noise for video-gamey explosions and harsh clanks
- LFO per voice
- transient generator per voice which can sweep the loudness, VCO pitch, and noise sweep

#### Rich IO
- each voice has
    - pad in: input jack for drum pads
    - logic in: input jack for trigger inputs
    - pedal: jack to connect a footswitch which shortens the decay time of the envelope, for closed/open hi-hat sounds and similar
    - cv in: control voltage input for the VCO and noise sweep


#### Voltage controlled filter
- single state variable type filter with lowpass, bandpass, and highpass available
- LFO and envelope modulation for the VCF
- each voice can be routed to the VCF or straight to the output
- external audio input
- external CV input

### Notes:
- this is an old project that I built on pad-per-hole prototyping board. There is no PCB layout.
- I would probably do a few things differently today, but it does work well and sounds good.
- there are a few missing values, and some that I had to guess about, it's probably pretty close to right, but there might be some errors.
