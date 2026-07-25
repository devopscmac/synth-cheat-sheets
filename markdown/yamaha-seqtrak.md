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

## Factory Sound Categories

Both SYNTH (AWM2) and DX (FM) tracks organize 2,032 presets into 15 shared categories. Drum tracks have their own 15 drum categories. SAMPLER tracks use 15 sample categories (392 presets).

### Synth & DX Categories (AWM2 + FM)

| # | Category | Description |
|---|---|---|
| 1 | **Bass** | Acoustic, synth, FM basses — sub, plucked, distorted |
| 2 | **Synth Lead** | Mono leads — square, saw, FM, ring-mod, brass-style |
| 3 | **Piano** | Acoustic grands, uprights, FM pianos, DX7 classics |
| 4 | **Keyboard** | EPs, clavinets, harpsichords — Wurly, Rhodes, DX EPs |
| 5 | **Organ** | Tonewheel, pipe, accordion, combo organs — jazz/rock/classical |
| 6 | **Pad** | Warm, evolving, atmospheric — saw pads, PWM, sweep pads |
| 7 | **Strings** | Orchestral ensembles, solo strings, synth strings, PWM |
| 8 | **Brass** | Trumpet, trombone, French horn, synth brass, hits |
| 9 | **Woodwind** | Flute, clarinet, sax, oboe, bassoon — solo & ensemble |
| 10 | **Guitar** | Acoustic, electric, nylon, wah, distorted, FM chorus |
| 11 | **World** | Koto, shamisen, sitar, ethnic winds & strings |
| 12 | **Mallet** | Marimba, vibraphone, xylophone, glockenspiel |
| 13 | **Bell** | Music box, tubular bells, crystal, digital FM bells |
| 14 | **Rhythmic** | Arpeggiated versions of synth presets — bass, lead, pad |
| 15 | **SFX** | Sound effects — sirens, choppers, beats, sweeps |

### Drum Categories

| # | Category | # | Category | # | Category |
|---|---|---|---|---|---|
| 1 | Kick | 6 | Closed HiHat | 11 | Tom |
| 2 | Snare | 7 | Open HiHat | 12 | Bell |
| 3 | Rim | 8 | Shaker / Tambourine | 13 | Conga / Bongo |
| 4 | Clap | 9 | Ride | 14 | World |
| 5 | Snap | 10 | Crash | 15 | SFX |

### SAMPLER Categories

| # | Category | # | Category |
|---|---|---|---|
| 1 | Vocal Count | 9 | Ambient / Soundscape |
| 2 | Vocal Phrase / Chant | 10 | SFX |
| 3 | Singing Vocal | 11 | Scratch |
| 4 | Robotic Vocal / Effect | 12 | Nature / Animals |
| 5 | Riser | 13 | Hit / Stab / Musical Instrument |
| 6 | Laser / Sci-Fi | 14 | Percussion |
| 7 | Impact | 15 | Recorded Sound |
| 8 | Noise / Distorted Sound | | |

Select a sound by pressing a Track knob then turning Sound Design knob 1 on Page 1. **Category Jump**: hold Sound Design knob 1 + press a Drum key (1–15) to jump to the first sound in the corresponding category.

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

## Advanced Sound Design (AWM2 Synth)

Beyond the 3 hardware Sound Design pages, deeper parameters are accessible via the SEQTRAK app. SYNTH 1 and SYNTH 2 share the same engine.

### AEG (Amplitude Envelope Generator)

| Stage | Hardware Page 2 | App (full) |
|---|---|---|
| **Attack** | Knob 1 (ATTACK) | 0–127 |
| **Decay** | Knob 2 (DECAY/RELEASE) | 0–127 |
| **Sustain** | — | 0–127 (fixed at max on hardware) |
| **Release** | — | linked to Decay on hardware |

### Filter

| Parameter | Hardware | App |
|---|---|---|
| **Type** | — | LP24, LP18, LP12, HP24, HP12, BP12, BP6, Through |
| **Cutoff** | Page 2 Knob 3 | 0–127 |
| **Resonance** | Page 2 Knob 4 | 0–127 |
| **Key Follow** | — | -100% to +100% |
| **Velocity Sensitivity** | — | -100% to +100% |
| **Env Depth** | — | -100% to +100% |

### LFO

| Parameter | App Only |
|---|---|
| **Wave** | Sine, Triangle, Saw Up, Saw Down, Square, Sample & Hold, Random S&H |
| **Speed** | 0–127 (free) or tempo-synced (1/64t – 8 bars) |
| **Delay** | 0–127 |
| **Depth** | 0–127 |
| **Destination** | Pitch, Filter, Amplitude, Pan |
| **Key Sync** | On/Off |

### Advanced Settings (App Only)

- **Portamento** — Time 0–127, Mode (Always, Fingered)
- **Arpeggiator** — Type (8 patterns), Direction (Up/Down/UpDown/Random), Gate 0–127, Speed 0–127, Hold On/Off
- **Track Effect** — Insert effect per track (selected with sound, adjustable in app)
- **EQ** — 2-band shelving (High Gain, Low Gain) on Page 3 hardware knobs

## Advanced Sound Design (DX FM)

The DX track uses the same 4-operator FM engine as the reface DX. Hardware Page 2 exposes the core FM parameters; the app provides full operator-level editing.

### Hardware FM Parameters (Page 2)

| Knob | Parameter | Effect |
|---|---|---|
| **1** | **ALGORITHM** | Selects operator routing configuration (1–8) |
| **2** | **MOD AMOUNT** | Overall modulation intensity (global FM depth) |
| **3** | **MOD FREQ** | Operator frequency ratio / fixed frequency |
| **4** | **MOD FEEDBACK** | Feedback amount for self-modulating operators |

### Algorithm Overview (1–8)

The 4 operators (OP1–OP4) can be arranged in serial, parallel, or mixed configurations:

| Algorithm | Structure | Best For |
|---|---|---|
| **1** | 4-op serial chain | Rich harmonic stacks, complex evolving tones |
| **2** | 3-op → 1 (stacked) | Brass, resonant filters |
| **3** | 2+2 parallel | Dual-timbral sounds, layered EPs |
| **4** | 2→1 + 1 (fork) | Clavs, plucks, percussive tones |
| **5** | 2→1 + 1 (parallel) | Bell-like, glassy textures |
| **6** | 1→1 + 2 (split) | Bass + harmonic accent |
| **7** | 4-op all parallel | Additive-style, organ-like |
| **8** | OP1→OP2 (self-fb) | Distorted, metallic, aggressive leads |

All use OP4 as the final output carrier; OP1–OP3 act as modulators.

### Full Operator Editing (App Only)

Each of the 4 operators has:

| Parameter | Range | Notes |
|---|---|---|
| **Frequency Ratio** | 0.5 – 32.0 | Coarse pitch multiplier |
| **Fixed Frequency** | 0 – 12000 Hz | Overrides ratio when enabled |
| **Level** | 0–127 | Output level of operator |
| **Velocity Sensitivity** | -100% to +100% | How hard playing affects level |
| **Envelope** | A/D/S/R | 4-stage rate/level envelope per operator |
| **Feedback** | 0–7 | Self-oscillation (OP4 only in some algos) |

### FM Sound Design Tips

- Start with a simple algorithm (7 or 8) and enable operators incrementally.
- Low MOD AMOUNT + high MOD FREQ ratio produces bell/metalic tones.
- High MOD AMOUNT + low MOD FREQ ratio produces overdriven/distorted tones.
- Ratios of 1:1 → octave, 2:1 → 5th, 3:2 → 5th above, 4:1 → 2 octaves.
- Use SOUND SELECT on Page 1 to pick a DX preset, then tweak MOD AMOUNT (Page 2 knob 2) for quick variation.
- Assign LFO to pitch for vibrato, to filter for wah, or to amplitude for tremolo (via app).
- Save edited sounds by holding [ALL] + pressing Sound Design knob 1 — appended as "_editNN".

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
