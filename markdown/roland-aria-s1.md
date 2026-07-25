# Roland AIRA Compact S-1 — Cheat Sheet

*Portable 4-voice polysynth inspired by the SH-101. ACB analog modeling, 64-step sequencer, OSC Draw/Chop, D-Motion, onboard delay/reverb/chorus. Battery-powered (~4.5h), USB-C audio/MIDI.*

## Top Panel Layout

| Section | Controls |
|---|---|
| **Jacks** | SYNC IN/OUT, MIX IN, MIX OUT/HEADSET, USB-C, VOLUME knob |
| **Display / Transport** | 4-digit LED, TEMPO/VALUE knob, SHIFT, HOLD, PLAY, REC |
| **LFO** | RATE knob, WAVE FORM knob (saw, inv saw, triangle, square, RND, noise) |
| **Oscillator** | RANGE (octave), LFO depth, Square level, Saw level, SUB level, NOISE level |
| **Filter** | FREQ (cutoff), RESO (resonance), LFO depth, ENV depth |
| **ENV** | ADSR: ATTACK, DECAY, SUSTAIN, RELEASE |
| **EFX** | DELAY level, REVERB level, D-MOTION button |
| **Keyboard pads** | 26 multi-function pads: 2-octave keyboard + step pads 1–16 |
| **Function buttons** | PATTERN (step loop), STEP (key transpose), KYBD |

## Signal Flow

```text
VCO (Square/Saw/Sub/Noise) → Filter (LPF) → Amp → EFX (Delay/Reverb/Chorus) → MIX OUT
        ↑                         ↑           ↑
       LFO                       ENV        ENV
  (rate/waveform)           (ADSR)       (ADSR)
```

## Oscillator Section

| Knob | Normal | SHIFT + |
|---|---|---|
| RANGE | Octave (16′, 8′, 4′, 2′) | Fine tune |
| LFO | LFO → pitch modulation depth | OSC Chop Overtone |
| Square (□) | Square wave level | Pulse width (or OSC Draw Multiply) |
| Saw (△) | Saw wave level | OSC Draw SW |
| SUB | Sub oscillator level | OSC Chop Comb |
| NOISE | Noise level | Noise mode (or Riser control) |

**OSC DRAW**: Create custom waveforms by drawing on the step pads (SHIFT + pad 5). Multiply, Step, and Slope modes.

**OSC CHOP**: Cut waveforms into sections and emphasize harmonics (SHIFT + pad 6). Overtone and Comb parameters.

## Filter Section

| Knob | Normal | SHIFT + |
|---|---|---|
| FREQ | Cutoff frequency | — |
| RESO | Resonance | — |
| LFO | LFO → cutoff modulation depth | — |
| ENV | Envelope → cutoff modulation depth | Keyboard follow |

Low-pass filter derived from SH-101 architecture. 24 dB/oct.

## ENV Section (ADSR)

| Knob | Normal |
|---|---|
| ATTACK | Time to reach peak |
| DECAY | Time to fall to sustain level |
| SUSTAIN | Level during sustain |
| RELEASE | Time to fade to zero |

## EFX Section

| Knob | Normal | SHIFT + |
|---|---|---|
| DELAY | Delay level (wet/dry) | Delay time |
| REVERB | Reverb level (wet/dry) | Reverb time |

Reverb types: Room, Hall, Plate, Spring. Delay syncs to tempo. Chorus accessible via menu (SHIFT + STEP + pad 15): 4 types (normal, fast, Leslie, chilled).

## Sequencer

- **64 patterns**, **64 steps** each
- Modes: **Real-time** and **Step** recording
- **Motion recording**: hold a step + turn any knob to automate parameters
- Per-step parameters: velocity, gate time, probability, sub steps, last step
- **Step loop**: SHIFT + PATTERN — hold steps to loop a section live
- **Key transpose**: SHIFT + STEP + pads to shift the key
- **Pattern scale**: PATTERN + TEMPO/VALUE knob
- **Master probability**: STEP + TEMPO/VALUE knob

## Performance Features

### D-Motion

- Press **D-MOTION** — tilting the unit controls pitch/mod/assigned parameters
- SHIFT + D-MOTION to select destination (pitch, filter, LFO, etc.)

### Arpeggiator

- SHIFT + pad 9 (ARP) to toggle. 8 phrase types (up, down, up/down, random, chord, etc.)
- Hold pads to latch arpeggiated notes

### Riser

- Turn NOISE knob (with Riser mode on) — adds rising/falling sweep effects
- Toggle Riser mode: SHIFT + EXIT + ENTER

### Manual Mode

- SHIFT + HOLD — applies current knob positions to the selected pattern's sound
- Reload saved sound: SHIFT + EXIT + POLY (or via menu `rL.Sd`)

## Key Buttons & Shift Combos

| Action | Result |
|---|---|
| **PATTERN** | Enter pattern select mode |
| **SHIFT + PATTERN** | Step loop mode |
| **STEP** | Toggle step pads (white keys = steps 1–16) |
| **SHIFT + STEP** | Key transpose |
| **SHIFT + REC** | Metronome toggle |
| **SHIFT + HOLD** | Manual (apply knobs to pattern) |
| **SHIFT + EXIT + POLY** | Reload saved sound (rL.Sd) |
| **SHIFT + OCT– + OCT+** | Reset octave |
| **SHIFT + pad 9 (ARP)** | Arpeggiator on/off |
| **SHIFT + pad 15 (MENU)** | System menu (chorus, LFO sync, etc.) |
| **PATTERN + TEMPO/VALUE** | Pattern scale |
| **STEP + TEMPO/VALUE** | Master probability |

## Menu Items (SHIFT + STEP + pad 15)

| Item | Parameter |
|---|---|
| LFO Modulation Depth | LFO depth |
| LFO Mode | Normal, trigger, one-shot |
| LFO Key Trigger | Off, on |
| LFO Sync | Off, on (tempo-sync) |
| Oscillator Bend Sens | Pitch bend range |
| Filter Bend Sens | Filter bend range |
| Chorus | Off, 1–4 types |
| Noise Mode | Normal, Riser |
| Poly Mode | Mono, Poly, Unison, Chord |
| Chord Voice 2/3/4 SW | Chord voicing on/off |
| Chord Voice 2/3/4 Key Shift | Chord interval |
| Portamento Mode | Auto, off |
| Keyboard Transpose | Key shift |

## Connectivity

- **SYNC IN/OUT** — mini-jack sync with other AIRA Compact gear
- **MIX IN** — external audio blend
- **MIX OUT/HEADSET** — stereo out / headphones
- **USB-C** — audio + MIDI + charging
- **MIDI IN/OUT** — TRS Type A (optional BOSS TRS-MIDI cable)
- **AIRA Link** — multi-channel USB audio with MX-1

## Specs

| Spec | Value |
|---|---|
| Sound engine | ACB (Analog Circuit Behavior) |
| Polyphony | 4 voices |
| Oscillators | Square, Saw, Sub (1 oct down), Noise |
| Custom waveforms | OSC Draw (step/slope/multiply), OSC Chop (overtone/comb) |
| Patterns | 64 (64 steps each) |
| Effects | Delay, Reverb (Room/Hall/Plate/Spring), Chorus (4 types) |
| Battery | Li-ion, ~4.5 h use, ~3 h charge |
| Dimensions | 188 × 106 × 36 mm |
| Weight | 305 g |

## MIDI Implementation

### Channel Map

| Device | Default Ch |
|---|---|
| Synth | Ch 3 |
| Program change | Ch 16 |

### MIDI Implementation Chart

| Function | Transmitted | Recognized |
|---|---|---|
| **Basic channel** | 3 (synth), 16 (PC) | 3, 16 |
| **Mode** | Mode 3 (Omni off, Poly) | Mode 3 |
| **Note number** | 0–127 | 0–127 |
| **Velocity (Note on)** | o | o |
| **Velocity (Note off)** | x | x |
| **Aftertouch** | x | x |
| **Pitch bend** | x | o |
| **Control change** | o | o |
| **Program change** | o (0–63) | o (0–63) |
| **System exclusive** | x | x |
| **Clock (F8)** | o | o |
| **Start (FA)** | o | o |
| **Continue (FB)** | x | x |
| **Stop (FC)** | o | o |
| **All sound off (120)** | o | o |
| **Reset all controllers (121)** | x | x |
| **All notes off (123)** | x | o |
| **Active sensing** | o | o |

### CC Control List

| CC | Parameter | Front Panel |
|---|---|---|
| 1 | Modulation Wheel | — |
| 3 | LFO Rate | LFO RATE knob |
| 5 | Portamento Time | SHIFT + PORTA TIME |
| 10 | Pan | — |
| 11 | Expression Pedal | — |
| 12 | LFO Waveform | LFO WAVE FORM knob |
| 13 | OSC LFO | OSCILLATOR LFO knob |
| 14 | OSC Range | OSCILLATOR RANGE knob |
| 15 | OSC Pulse Width | SHIFT + PWM DEPTH |
| 16 | OSC PWM Source | SHIFT + PWM SRC |
| 17 | LFO Mod Depth | SHIFT + pad 15 (MENU) |
| 19 | Square Level | OSCILLATOR □ knob |
| 20 | Saw Level | OSCILLATOR △ knob |
| 21 | Sub Level | OSCILLATOR SUB knob |
| 22 | Sub Oct Type | SHIFT + SUB OCT |
| 23 | Noise Level | OSCILLATOR NOISE knob |
| 24 | Filter Env Depth | FILTER ENV knob |
| 25 | Filter LFO Depth | FILTER LFO knob |
| 26 | Filter Keyboard Follow | SHIFT + FILTER KYBD |
| 28 | Amp Env Mode SW | SHIFT + AMP |
| 29 | Env Trigger Mode | SHIFT + ENV TRG |
| 30 | Env Sustain | ENV SUSTAIN knob |
| 64 | Damper Pedal | — |
| 65 | Portamento | SHIFT + PORTA ON |
| 71 | Filter Resonance | FILTER RESO knob |
| 72 | Env Release | ENV RELEASE knob |
| 73 | Env Attack | ENV ATTACK knob |
| 74 | Filter Frequency | FILTER FREQ knob |
| 75 | Env Decay | ENV DECAY knob |
| 76 | Fine Tune | SHIFT + OSC RANGE |
| 77 | Transpose | SHIFT + KEY TRANSPOSE |
| 78 | Noise Mode | SHIFT + pad 15 |
| 79 | LFO Mode | SHIFT + LFO RATE |
| 80 | Poly Mode | SHIFT + POLY |
| 81–83 | Chord Voice 2/3/4 SW | SHIFT + POLY |
| 85–87 | Chord Voice 2/3/4 Key Shift | SHIFT + POLY |
| 89 | Reverb Time | SHIFT + REVERB knob |
| 90 | Delay Time | SHIFT + DELAY knob |
| 91 | Reverb Level | REVERB knob |
| 92 | Delay Level | DELAY knob |
| 93 | Chorus Type | SHIFT + pad 15 |
| 102 | OSC Draw Multiply | SHIFT + OSC DRAW |
| 103 | OSC Chop Overtone | SHIFT + OSC CHOP |
| 104 | OSC Chop Comb | SHIFT + OSC CHOP |
| 105 | LFO Key Trigger | SHIFT + pad 15 |
| 106 | LFO Sync | SHIFT + LFO WAVE (v1.02) |
| 107 | OSC Draw SW | SHIFT + OSC DRAW |

---
*Source: Roland official S-1 Owner's Manual (Version 1.02)*
