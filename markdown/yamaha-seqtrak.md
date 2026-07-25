# Yamaha SEQTRAK — Cheat Sheet

*Portable groovebox with AWM2 + FM synthesis, 11-track sequencer, sampling, and Wi-Fi/Bluetooth. Rechargeable battery, built-in speaker and mic.*

## Top Panel Layout

| Section | Controls |
|---|---|
| **Drum** | 7 track knobs (KICK, SNARE, CLAP, HAT 1, HAT 2, PERC 1, PERC 2), 16 Drum keys (step sequencer grid) |
| **Synth** | 4 track knobs (SYNTH 1, SYNTH 2, DX, SAMPLER), 7 Synth keys (chromatic scale) |
| **Sound Design & FX** | 4 Sound Design knobs, Sound Design Page button, FX knob, MASTER/SINGLE switch, 3 touch sliders (FX LEVEL / HIGH PASS / REPEATER), CLEAR FX button, UNDO/REDO button |
| **Transport & Mode** | P/PLAY button, Record key, SOLO button, MUTE button, PAGE button, PROJECT button, BAR LENGTH, OCTAVE, SCALE, KEY, REC SAMPLE button |
| **Global** | [ALL] knob, VOL+/VOL− buttons, Global Meter (LED ring), Index display |
| **Top jacks** | PHONES (stereo mini), AUDIO IN (stereo mini), USB-C (power, audio, MIDI), MIDI IN/OUT (breakout cable) |

## Project / Track / Pattern Structure

| Concept | Details |
|---|---|
| **Projects** | 8 per device (managed via app for backup) |
| **Tracks** | 11 total — 7 Drum, 3 Synth (SYNTH 1 AWM2, SYNTH 2 AWM2, DX FM), 1 SAMPLER |
| **Patterns** | Up to 6 per track |
| **Steps** | Up to 128 per pattern |
| **Song/Scene** | Chain patterns across tracks into song arrangements (via app) |

## Drum Tracks

| Track Knob | Default Sound |
|---|---|
| **KICK** | Kick drum |
| **SNARE** | Snare drum |
| **CLAP** | Clap / snap |
| **HAT 1** | Closed hi-hat |
| **HAT 2** | Open hi-hat |
| **PERC 1** | Percussion 1 |
| **PERC 2** | Percussion 2 |

**Track types** (OS v2.0): Press & hold a Drum track knob, then hold a Drum key 5 sec to change:
- **Drum** (key 9) — default, single sound per track, step input
- **DrumKit** (key 10) — assign 7 drum sounds to Synth keys, play chromatically
- **Synth** (key 11) — turn drum track into AWM2 synth sound, play via Synth keys

## Synth Tracks

| Track Knob | Engine | Polyphony |
|---|---|---|
| **SYNTH 1** | AWM2 (sample-based) | 128 |
| **SYNTH 2** | AWM2 (sample-based) | 128 |
| **DX** | FM (4 operators) | 8 |

- Mono/Poly/Chord modes via Sound Design knob 2 on Page 1
- CHORD mode: hold [ALL] + Synth key to edit chord voicing (up to 4 notes)
- **Keyboard Input mode**: hold [ALL] + [KEY] — Drum keys become a piano keyboard

## Sampling Workflow

1. Press [SAMPLER] knob to select SAMPLER track.
2. Press a **Synth key** to assign the sample slot (1–7). Selected key flashes red.
3. Press **[REC SAMPLE]** to start recording (built-in mic by default; up to 16 sec).
4. Press **[REC SAMPLE]** again to stop. Sample auto-normalizes.
5. Press the Synth key to audition.

**Change source**: Hold [REC SAMPLE] 2 sec + press lit Drum key to cycle: built-in mic / AUDIO IN / USB audio / resample.

**Resample**: Set source to resample, play patterns, press [REC SAMPLE] to capture the mix.

**Cancel sampling**: Hold [DELETE] + [REC SAMPLE].

**Monitoring mode**: Hold [REC SAMPLE] + [VOL+] to check input level on Global Meter.

## Sound Design Pages

Press a **Track knob** to select a track, then use **Sound Design knobs 1–4** and **Page button** to adjust parameters.

### Drum Track (Type: Drum)

| Page | Knob 1 | Knob 2 | Knob 3 | Knob 4 |
|---|---|---|---|---|
| **1** | SOUND SELECT | ATTACK | DECAY | PITCH |
| **2** | PAN | VOLUME | FILTER CUTOFF | FILTER RESONANCE |
| **3** | REVERB SEND | DELAY SEND | EQ HIGH | EQ LOW |

### Synth Track (SYNTH 1 / 2)

| Page | Knob 1 | Knob 2 | Knob 3 | Knob 4 |
|---|---|---|---|---|
| **1** | SOUND SELECT | MONO/POLY/CHORD | PAN | VOLUME |
| **2** | ATTACK | DECAY/RELEASE | FILTER CUTOFF | FILTER RESONANCE |
| **3** | REVERB SEND | DELAY SEND | EQ HIGH | EQ LOW |

### DX Track (FM)

| Page | Knob 1 | Knob 2 | Knob 3 | Knob 4 |
|---|---|---|---|---|
| **1** | SOUND SELECT | MONO/POLY/CHORD | PAN | VOLUME |
| **2** | ALGORITHM | MOD AMOUNT | MOD FREQ | MOD FEEDBACK |
| **3** | REVERB SEND | DELAY SEND | EQ HIGH | EQ LOW |

### SAMPLER Track

| Page | Knob 1 | Knob 2 | Knob 3 | Knob 4 |
|---|---|---|---|---|
| **1** | SOUND SELECT | START POINT | END POINT | LOOP ON/OFF |
| **2** | LOOP LENGTH | ATTACK | DECAY/RELEASE | PITCH |
| **3** | PAN | VOLUME | FILTER CUTOFF | FILTER RESONANCE |

## Effects Architecture

Three effect layers applied in order:

1. **Track effects** — per-track, changes with sound selection
2. **Send effects** — shared across all tracks (REVERB × 12 types, DELAY × 9 types)
3. **Master effects** — applied to final mix (85 types including FILTER, REVERB, DELAY, COMPRESSOR, DISTORTION, MODULATION, DUCKER, OTHER)

### Controlling Effects

| Control | Function |
|---|---|
| **MASTER/SINGLE switch** | MASTER = effect on all tracks, SINGLE = effect on selected track only |
| **[FX] knob** | Scroll through effect presets (85 MASTER / 85 SINGLE types in 8 categories) |
| **[FX LEVEL] slider** | Effect send level / wet-dry mix |
| **[HIGH PASS] slider** | High-pass filter cutoff (always global) |
| **[REPEATER] slider** | Beat repeat / stutter (always global) |
| **[CLEAR FX] button** | Minimize current effect level |
| **FX Page button** | Switch slider parameter pages |
| **Mixer mode** | Per-track volume, pan, reverb/delay send levels |

## Sequencer Operations

| Action | How |
|---|---|
| **Select track** | Press a Track knob |
| **Step input (Drums)** | Press Drum keys to toggle steps on/off |
| **Step input (Synth/Sampler)** | Hold [PAGE] + press Synth/SAMPLER knob to enter Step mode |
| **Real-time record** | Press Record key, play Synth keys, press Record again to stop |
| **Pattern length** | Hold [PAGE] + turn Drum Track knob (1–128 steps) |
| **Copy pattern** | Hold Track knob or [ALL] + press Drum key 2 sec |
| **Paste pattern** | Hold Track knob + [PAGE] + press Drum key |
| **Copy steps** | Hold a Drum key 2 sec (Synth/Sampler tracks must be in Step mode) |
| **Paste steps** | Hold [PAGE] + press Drum key |
| **Parameter Lock** | Hold a lit Drum key + turn Sound Design knob — step lights purple |
| **ALL knob** | Turn to change all 11 track patterns simultaneously |
| **Swing** | Adjust via app or hold [ALL] + turn while in appropriate mode (OS v2.0) |
| **BAR LENGTH** | Change pattern length for Synth / SAMPLER tracks (also Drum in OS v2.0) |

## Key Shortcuts

| Action | Result |
|---|---|
| **[ALL] + [KEY]** | Keyboard Input mode (Drum keys become piano) |
| **[ALL] + [REC SAMPLE]** | Toggle count-in on/off for sampling |
| **Hold [ALL] + Synth key** | Edit chord voicing (in CHORD mode) |
| **Hold [DELETE] + [REC SAMPLE]** | Cancel sampling in progress |
| **Hold [REC SAMPLE] + [VOL+]** | Monitoring mode (check input level) |
| **Hold [MUTE] + Synth key** | Mute/unmute sample on SAMPLER track |
| **Hold [PAGE] + Track knob** | Enter Step Input mode (Synth/SAMPLER) |
| **[CLEAR FX]** | Reset effect to minimum |
| **[UNDO/REDO]** | Undo/redo sound and effect parameter changes |
| **Hold [PROJECT] + Drum key** | Load project (1–8) |
| **[SOLO]** | Solo selected track |

## Connectivity

- **USB-C** — power (PD), audio interface (44.1 kHz / 24-bit), MIDI to host/device
- **PHONES** — stereo mini jack (mutes built-in speaker)
- **AUDIO IN** — stereo mini jack for sampling external audio
- **MIDI IN/OUT** — via included breakout cable (TRS to 5-pin DIN)
- **Bluetooth** — MIDI to/from SEQTRAK app
- **Wi-Fi** — wireless WAV sample transfer with SEQTRAK app
- **Built-in mic** — MEMS microphone
- **Built-in speaker** — 2.3 cm, 1 W

## Specs at a Glance

| Spec | Value |
|---|---|
| Sound engines | AWM2 (128 voices) + FM 4-op (8 voices) |
| Preset waveforms | 800 MB (16-bit equiv), 2032 sounds |
| User waveform memory | 500 MB |
| Sampler slots | 7 (up to 16 sec each) |
| Preset sampler sounds | 392 |
| Tracks | 11 (7 Drum + 3 Synth + 1 Sampler) |
| Patterns per track | 6 |
| Max steps per pattern | 128 |
| Projects | 8 |
| Effects | 85 Master × 85 Single + 12 Reverb + 9 Delay |
| Sampling rate | 44.1 kHz / 24-bit |
| Battery | Li-ion 2100 mAh, ~3–4 hrs, charge 3–5 hrs |
| Power | USB-C PD (5V / 1.5A+), 6W |
| Dimensions | 343 × 97 × 38 mm |
| Weight | 0.5 kg |
| App | SEQTRAK app (Mac, PC, iOS, Android) |

## Quick Tips

- Press a **Track knob** while stopped to audition the sound without playing a pattern.
- Turn **Sound Design knobs** while pressing them for larger/sweeping parameter changes.
- **Parameter Lock** (hold lit Drum key + turn a Sound Design knob) lets you automate filter, pitch, FX, etc. per step.
- **ALL knob** changes patterns for all 11 tracks at once — great for live remixing.
- In **Mixer mode** you can adjust per-track volume, pan, reverb/delay sends.
- **Song/Scene mode** (via app) lets you chain patterns into full arrangements.
- Use the **SEQTRAK app** for deep sound editing, visualizer, sample management, and firmware updates.
- DX track excels for FM basses, metallic percussion, and glassy pads — tweak the algorithm and modulator parameters on Page 2.
- **Chord mode**: set a Synth track to CHORD on Page 1, then hold [ALL] + a Synth key to customize which notes form the chord.
- **Keyboard Input mode** ([ALL] + [KEY]) turns the 16 Drum keys into a piano layout for melodic input.

---
*Source: Yamaha SEQTRAK User Guide v1.20 / Quick Operation Guide, yamahasynth.com*
