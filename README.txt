# StyloPoly - Version: [1.0]

Date: 2024-01-07
Name: Benjamin Dehli
Profile: pianobook.co.uk/profile/benjamindehli

## Included formats

- Decent Sampler

## Description

A Dubreq Stylophone S-1 with some added features

## Technical specification

|                                 | Sample rate | Bit depth | Channels   | Number of files | File size |
|--------------------------------:|------------:|----------:|------------|----------------:|----------:|
|           **Samples**           |      48 kHz |    24 bit | 1 (mono)   |             163 |  68.90 MB |
| **Impulse responses (effects)** |      48 kHz |    24 bit | 2 (stereo) |               4 |   3.60 MB |
| **Impulse responses (speaker)** |      48 kHz |    24 bit | 1 (mono)   |               1 |  66.00 KB |

## User Interface

The user interface offers precise control over every aspect of the instrument and effects.
Explore parameters to refine your sound, including control over the audio mixer, envelope, pitch modulation with LFOs, high pass and low pass filters, velocity/dynamics, speaker simulator, and the immersive effects of echo and reverb.

### Keyboard

- Mono / Poly
  - Mono: Plays only one note at the time, like the original Stylophone
  - Poly: Plays multiple notes at the time
- Static / Dynamic
  - Determines whether the velocity should affect the volume of the samples

### Envelope

Shape your sound precisely with the Attack, Decay, Sustain, and Release parameters. Whether you desire a punchy, staccato tone or a smooth, lingering ambiance, the ADSR envelope allows you to tailor the dynamics to your liking.

- Attack
  - Attack time of the amplitude envelope for the three voices
- Decay
  - Decay time of the amplitude envelope for the three voices
- Sustain
  - Sustain level of the amplitude envelope for the three voices
- Release
  - Release time of the amplitude envelope for the three voices

### Samples volume

#### Mixer

The original Stylophone only lets you select one voice at a time, but with StyloPoly you can blend between all the three voices at the same time.

- Low
  - The sound of the Stylophone with the voice selector in position 1
- Middle
  - The sound of the Stylophone with the voice selector in position 2
- High
  - The sound of the Stylophone with the voice selector in position 3

#### Noise

- Attack
  - Pops and crackles when the stylus hits the "keyboard"
- Release
  - Pops and crackles when the stylus releases from the "keyboard"

### Vibrato

The depth and rate knobs enable you to modulate the pitch of the sound with the desired depth and rate using a Low-Frequency Oscillator (LFO). With both controls in middle position you have approximately the same vibrato as the original Stylophone.

- Depth
  - Adjust the depth to introduce subtle or pronounced variations in pitch
- Rate
  - Determines the speed at which the modulation occurs

### Output

- Line out
  - The direct sound of the line output
- Speaker
  - The sound of the internal speaker miced with a Shure SM57

### High Pass Filter and Low Pass Filter

StyloPoly has a high pass filter and a low pass filter. The high pass filter ranges from 20 Hz to 2000 Hz and the low pass filter ranges from 200 Hz to 22000 Hz.

- Off / On
  - Turns on or off the filter
- Frequency
  - Cutoff frequency for the filter
- Resonance
  - Amount of resonance at cutoff frequency

### Effects

These effects are achieved using carefully crafted impulse responses. The echo effect employs a Fulltone Tube Tape Echo recorded twice for stereo, while the reverb effect draws from a Chase Bliss Audio & Meris CXM 1978 reverb pedal with a room setting.

#### Echo

Select from two distinctive echo options: the short echo, delivering a classic slapback effect, and the long echo, characterized by a slower decay and numerous repeats.

- Off / On
  - Turns the echo on and off
- Short / Long
  - Switches between a short slapback echo and a long echo with slow repeats and high feedback
- Mix
  - Mix between direct signal and echo signal

#### Reverb

You'll also find two reverb effects: the short reverb, evoking the intimacy of a small room, and the long reverb, enveloping your sound in the vastness of a spacious environment.

- Off / On
  - Turns the reverb on and off
- Short / Long
  - Switches between a short/small room reverb and a long/big room reverb
- Mix
  - Mix between direct signal and reverb signal

### Preset

Some presets are true to the original Stylophone and some presets take advantage of the additional features of StyloPoly. The presets only affects the controls already available from the GUI. They are not meant to sound like a real piano, harpsichord, clavinet, etc. The preset names are more of a way to describe the timbre.
