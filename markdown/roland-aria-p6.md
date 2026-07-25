# Roland AIRA Compact P-6 — Cheat Sheet

*Creative phrase sampler, part of Roland's AIRA Compact series. Battery-powered, 48-sample memory, 16-voice sample playback + 4-voice granular.*

## Top Panel Layout

| Section | Controls |
|---|---|
| **Display / Common** | 4-digit LED display, TEMPO/VALUE knob, SHIFT, PATTERN, Play, Record |
| **Effects** | CTRL1–CTRL3 knobs, LOOPER, PITCH (FX), DELAY, FILTER, SCATTER, MFX (master effect on/off) |
| **Sample Edit** | PITCH, START, END, LEVEL knobs; SAMPLING, LO-FI, GATE, DELETE, LOOP buttons |
| **Banks** | A/E–D/H bank select buttons (4 banks × 2 = 8 groups of 6 pads → 48 samples) |
| **Pads & Keys** | Pads 1–6, GRANULAR pad, step/keyboard buttons, KYBD (keyboard mode) |
| **Rear/Top jacks** | CHARGE indicator, SYNC IN/OUT, MIX IN, MIX OUT/HEADSET, VOLUME knob, USB-C |

## Sampling Workflow

1. Press **[SAMPLING]** — button lights, ready to sample.
2. Select an **empty (blinking)** pad — occupied pads can't be selected; delete the existing sample first if needed.
3. Press **[SAMPLING]** again to start recording (pad lights, SAMPLING blinks).
4. Press **[SAMPLING]** once more to stop.
5. Device auto-processes the sample: displays `nor÷` (normalizing) → `donE` when finished.

**Step sampling**: automatically divides one long recording into equal segments across multiple pads — useful for chopping a beat or vocal phrase in one pass.

## Granular Synthesizer

The P-6's granular engine turns any sample into a morphing, evolving texture by slicing it into tiny grains and playing them back with independent control over position, size, density, and pitch.

### Assigning a Sample to Granular

| Method | Steps |
|---|---|
| **Assign via VOICE menu** | Press **[GRANULAR]** pad → press **[SHIFT]** + Step G (VOICE) → use VALUE knob to select `SMPL` → press **[C#]** (ENTER) → select desired sample pad → press **[C]** (EXIT) |
| **Shortcut** | Hold **[PATTERN]** + press **[GRANULAR]** → press the sample pad you want to assign |

### Playing the Granular Engine

- Press the **[GRANULAR]** pad to trigger the assigned sample in granular mode.
- Press **[KYBD]** to play the granular sound chromatically across the STEP KEYS.
- Enable polyphony: press **[SHIFT]** + **[GATE]** to set POLY — up to 4-voice polyphonic granular playback.
- The granular engine has its own independent **Filter**, **Amp/Filter Envelope**, and **Effects routing** (same as sample pads).

### Granular Parameters (Sample Edit Knobs)

| Knob | Function | Range / Notes |
|---|---|---|
| **PITCH** | Grain pitch / transpose | Coarse tuning of grains; -24 to +24 semitones |
| **START** | Grain position / spread | Controls where in the sample grains are read from — turn to scan through the source audio |
| **END** | Grain size | Length of each individual grain — small = grainy/glitchy, large = smoother/textural |
| **LEVEL** | Output level | Overall volume of the granular engine |

### Granular Parameters (VOICE Menu — SHIFT + VOICE)

| Parameter | Description |
|---|---|
| **SMPL** | Select/change the sample assigned to the granular pad |
| **GR.TYP** | Grain type/shape — affects the character of each grain envelope |
| **GR.DEN** | Grain density — how many grains are triggered per second |
| **GR.PAN** | Grain panning spread — stereo width of the granular texture |
| **GR.KEY** | Key tracking for grain parameters (on/off) |
| **G.ATK** | Grain attack time — how quickly each grain fades in |
| **G.DEC** | Grain decay time — how quickly each grain fades out |
| **G.DEP** | Modulation depth for grain parameters (via internal LFO) |
| **G.SPD** | Modulation speed for grain parameters |

### Sound Design Tips for Granular

- **Small grain size + high density** = smooth, pad-like textures.
- **Large grain size + low density** = glitchy, stuttering effects.
- **Turn START to scan** through the sample in real time — creates evolving, wavetable-like motion.
- **Resample** the granular output: press **[SAMPLING]**, select a pad, press **[SAMPLING]** again to capture the granular texture as a new sample — then apply effects, chop it, or layer it.
- **Apply MFX** to the granular engine: try Reverb, Chorus, Flanger, or Scatter for extreme transformation.
- **Polyphonic granular** (SHIFT + GATE) lets you play chords — great for ambient pads and dreamy textures.
- Sequence the GRANULAR pad in a pattern like any other pad — use motion recording on START (grain position) to sweep through the sample over time.

## Sample Edit Knobs (context-dependent)

The four knobs re-map depending on the current edit page:

| Page | PITCH | START | END | LEVEL |
|---|---|---|---|---|
| **Top / normal** | Coarse tune | Start point | End point | Sample level |
| **P.ENV (pitch envelope)** | Attack | Decay | Sustain | Release |
| **Voice (tone envelope)** | Attack | Decay | Sustain | Release |
| **Granular mode** | Grain pitch | Grain position/spread | Grain size | Level |
| **Filter** | Cutoff | Resonance | Env depth | Level |
| **Mixer** | Pan | Delay send | Reverb send | Level |

CTRL1–CTRL3 always control the active effect's parameters (or Delay/Reverb time & level).

## Key Buttons & Shift Combos

| Action | Result |
|---|---|
| **LOOP** | Toggle sample looping |
| **SHIFT + LOOP** | Cycle playback direction: forward → reverse → alternate |
| **GATE** | Toggle gate (one-shot) playback mode |
| **SHIFT + GATE** | Switch sample between monophonic and polyphonic |
| **LO-FI** | Toggle Lo-Fi degradation on the sample |
| **DELETE** | Delete the selected sample (frees the pad) |
| **GRANULAR pad** | Engage granular playback/synthesis on a sample |
| **KYBD** | Play pads chromatically like a keyboard |
| **PATTERN** | Enter pattern select / management mode |
| **SHIFT + QUANTIZE** | Toggle real-time input quantization |

## Sequencer / Pattern

- Step & real-time recording of patterns per pad.
- **Step input**: press step buttons to place triggers; hold a step button while turning **PITCH/START/END/LEVEL** to record a "motion" (parameter lock) into that step.
- Supports tie input, note copy/paste/insert, and editing individual steps.
- Patterns are organized per bank/pad group and can be chained via PATTERN mode.

## Effects (MFX) — 20 Types

| Effect | Key Parameters |
|---|---|
| DJFX Looper | Length, Speed, Loop SW |
| Chromatic PS | Pitch 1/2, Balance, Pan 1/2 |
| Sync Delay | Time, Feedback, Level, Damp (Low/High) |
| Filter + Drive | Cutoff, Resonance, Drive, Filter type, Low freq/gain |
| Scatter | Type, Depth, Scatter, Speed |
| Isolator | Low, Mid, High |
| Resonator | Root, Bright, Feedback, Chord, Panning, Env mod |
| Stopper | Depth, Rate, Resonance, Filter mod, Amp mod |
| Super Filter | Cutoff, Resonance, Filter type, Depth, Rate, Sync |
| Vinyl Sim | Frequency, Noise, Wow/Flutter |
| Cassette Sim | Tone, Hiss, Age, Drive, Wow/Flutter, Catch |
| Lo-Fi | Pre-filter, Lo-Fi type, Tone, Cutoff, Balance, Level |
| Reverb | Type, Time, Level, Low/High cut, Pre-delay |
| Chorus | Depth, Rate, Balance, EQ low/high, Level |
| Flanger | Depth, Rate, Manual, Resonance, Balance, Sync |
| Phaser | Depth, Rate, Manual, Resonance, Balance, Sync |
| Tremolo/Pan | Depth, Rate, Type, Wave, Sync |
| Ring Mod | Frequency, Sens, Balance, Polarity, EQ low/high |
| Crusher | Filter, Rate, Balance |
| Compressor | Sustain, Attack, Ratio, Level |

Dedicated one-touch effect buttons: **LOOPER, PITCH, DELAY, FILTER, SCATTER**; **MFX** enables/disables the full multi-effect chain. CTRL1–3 shape whichever effect is active.

## Connectivity

- **SYNC IN / OUT** — mini-jack sync with other AIRA Compact / Pocket Operator-style gear
- **MIX IN** — blend external audio into the master mix
- **MIX OUT/HEADSET** — stereo out, doubles as headphone jack (CTIA stereo)
- **USB-C** — audio + MIDI over USB, plus charging
- **MIDI over USB** — connect to DAWs/computers; full MIDI implementation in the manual

## Specs at a Glance

| Spec | Value |
|---|---|
| Max samples | 48 |
| Max sample time | ~23.7 sec (mono, 11.025 kHz) |
| Import format | WAV (Linear PCM) |
| Internal mic | Mono x 1 |
| Polyphony | 16 voices (sample), 4 voices (granular) |
| Effects | 20 multi-effect types + delay/reverb sends |
| Power | Li-ion battery, ~3 hrs use, ~3 hrs charge via USB-C, 500 mA draw |
| Dimensions | 188 (W) × 106 (D) × 37 (H) mm |
| Weight | 305 g (with battery) |

## Quick Tips

- Occupied pads must be **DELETE**d before re-sampling into them.
- Use **SHIFT + GATE** to make chords/layers possible on a single sample (polyphonic).
- **Motion recording**: hold a step + twist a knob to automate filter/pitch/level sweeps per step.
- GRANULAR pad turns any sample into a texture/pad source — see the Granular Synthesizer section above for full parameter details and workflow.
- **Resample granular output** to capture evolving textures as new samples — press SAMPLING, select a pad, record, then edit with standard sample tools.
- **Automate grain position** with motion recording: hold a step + turn START knob to sweep through the sample over time.
- SYNC IN/OUT lets you clock-sync multiple AIRA Compact units without MIDI cables.

## MIDI Implementation

### Channel Map

| Device | Default MIDI Ch | Notes |
|---|---|---|
| **Sample pads** | Ch 11 | Triggers pads Bank A1–H6 via notes 48–95 |
| **Granular sampler** | Ch 4 | Receives CC control for granular parameters |
| **Program change** | Ch 16 | Selects sample via program change (0–63) |
| **Auto (receive)** | Ch 15 | Receives CC + program change on this channel |

### Note Number → Pad Map (48 pads)

| Note Range | Bank | Pads |
|---|---|---|
| 48–53 (C3–F#3) | A | A1–A6 |
| 54–59 (G3–C#3) | B | B1–B6 |
| 60–65 (D4–G#4) | C | C1–C6 |
| 66–71 (A4–D#4) | D | D1–D6 |
| 72–77 (E5–A#5) | E | E1–E6 |
| 78–83 (B5–E#6) | F | F1–F6 |
| 84–89 (F6–A#6) | G | G1–G6 |
| 90–95 (B6–D#6) | H | H1–H6 |

Note numbers are used for pad selection only — pitch does not change per note.

### MIDI Implementation Chart

| Function | Transmitted | Recognized |
|---|---|---|
| **Basic channel** | 4 (granular), 11 (pads), 16 (PC) | 4, 11, 15 (auto), 16 (PC) |
| **Mode** | Mode 3 (Omni off, Poly) | Mode 3 |
| **Note number** | 48–95 (C3–B6) | 48–95 |
| **Velocity (Note on)** | o | o |
| **Velocity (Note off)** | x | x |
| **Aftertouch** | x | x |
| **Pitch bend** | x | x |
| **Control change** | o | o |
| **Program change** | o (0–63) | o (0–63) |
| **System exclusive** | x | x |
| **Song position** | x | x |
| **Song select** | x | x |
| **Clock (F8)** | o | o |
| **Start (FA)** | o | o |
| **Continue (FB)** | x | o |
| **Stop (FC)** | o | o |
| **All sound off (120)** | o | o |
| **Reset all controllers (121)** | o | o |
| **All notes off (123)** | o | o |
| **Active sensing** | o | o |

### Granular CC Parameters

| CC | Param | CC | Param |
|---|---|---|---|
| 3 | Grain Reverse Probability | 25 | Spread |
| 7 | Level | 26 | Filter Cutoff Key Follow |
| 9 | Auto Pan | 28 | Amp Switch |
| 10 | Pan | 29 | T.Env Mode |
| 12 | Filter Type | 30 | T.Env Sustain |
| 13 | Detune | 68 | Grain Timing Jitter |
| 14 | Level Jitter | 71 | Filter Resonance |
| 15 | Grain Shape | 72 | T.Env Release |
| 16 | Grain Time Key Follow | 73 | T.Env Attack |
| 17 | Lo-Fi Intensity | 74 | Filter Cutoff |
| 18 | Fine Tune | 75 | T.Env Decay |
| 19 | Head Position | 76 | Coarse Tune |
| 20 | Head Speed | 77 | T.Env Time Key Follow |
| 21 | Grains | 78 | Filter Velocity Sens |
| 23 | Grain Size | 79 | Start Mode |
| 24 | Filter Env Depth | | |

### Mixer / Bus / FX CC Parameters

| CC | Param | Notes |
|---|---|---|
| 84 | Output Bus Select | 0: Bus A, 1: Bus B, 2+: Effect |
| 85 | Send Delay | Delay send level |
| 86 | Send Reverb | Reverb send level |
| 87 | Lo-Fi Switch | 0: Off, 1+: On |
| 88 | Sample Select | Maps to pad sample (0–127 → 48 pads) |
| 89 | Reverb Time | — |
| 90 | Delay Time | — |
| 91 | Reverb Level | — |
| 92 | Delay Level | — |

### Sync / Transport

- P-6 syncs to external MIDI clock when MIDI clock source is set to AUTO or MIDI.
- Clock (F8), Start (FA), Stop (FC) transmitted and received.
- Continue (FB) treated same as Start on receive.
- Works with other AIRA Compact devices (T-8, J-6, S-1, E-4) via SYNC IN/OUT or MIDI.

---
*Source: Roland official P-6 Owner's Manual ([static.roland.com/manuals/p-6/en-US](https://static.roland.com/manuals/p-6/en-US/index.html))*
