# Teenage Engineering EP-40 Riddim — Cheat Sheet

*128 MB reggae / dub / dancehall sampler and composer. Same chassis and workflow as the EP-133 K.O. II, plus the **supertone** synth engine, **loop (LOP)** play mode, **live state**, a 7th send FX (phaser), and 400+ handcrafted sounds with 8 remixable artist tracks. Ships with the EP-2350 "ting" FX microphone.*

## Top Panel Layout

| Section | Controls |
|---|---|
| **Display** | Custom segmented display, 66 icons — step position, sound number, parameter values |
| **Mode** | SOUND, MAIN (home), TEMPO (BPM / time signature) |
| **Function** | FX, SAMPLE, KEYS (chromatic), TIMING (note interval / swing) |
| **Transport** | RECORD, PLAY, ERASE |
| **Navigation** | SHIFT, − / +, KNOB X, KNOB Y, FADER |
| **Pads** | 12 velocity- & pressure-sensitive pads (also numpad 0–9, dot, enter) |
| **Groups** | 4 group buttons (icons instead of A–D labels) — pattern select, undo, copy, paste |
| **Top jacks** | LINE IN (3.5 mm stereo), LINE OUT (3.5 mm stereo), SYNC IN/OUT, MIDI IN/OUT (TRS Type A), USB-C, power switch, volume knob |

## Project / Scene / Group / Pattern Structure

| Concept | Details |
|---|---|
| **Projects** | 9 per device |
| **Groups** | 4 per project, each with 12 pads |
| **Patterns** | 99 per group, 1–99 bars each |
| **Scenes** | 99 per project — snapshot of 1 pattern from each group |
| **Song mode** | Chain scenes into an arrangement (hold MAIN + ENTER) |
| **Sequencer** | 96 PPQN |

## Sound Library Map

| Range | Category |
|---|---|
| 1–99 | Kicks |
| 100–199 | Snares |
| 200–299 | Hi-hats |
| 300–399 | Percussion |
| 400–499 | Bass |
| 500–599 | Keys / melodic |
| 600–699 | FX, shouts, sirens, dub stabs |

999 sample slots total, 128 MB all user-writable. Transfer via **EP Sample Tool** over USB-C.

## Supertone Synth Engine

The first synth engine in the EP series — subtractive, velocity- and pressure-sensitive, with classic reggae legacy bass/lead tones and dedicated dub sirens.

**Select a supertone**: hold **SOUND** + press the **dot** pad to enter supertone selection, then press pads **0–9** to pick one of the ten supertone sounds.

**Tweak on the fly**: in MAIN mode, hold the supertone's pad and turn **KNOB X** / **KNOB Y**.

**Edit and save**: **SHIFT + SOUND** → page with **−** / **+** to the supertone page. Hold **SHIFT + SOUND** for 2 s to save.

### Supertone Presets & Exposed Parameters

Each preset exposes exactly two editable parameters; the rest of the engine is fixed per preset.

| Preset | KNOB X | KNOB Y | Character |
|---|---|---|---|
| **SU.0** | Tone | Age | Vintage-voiced bass |
| **SU.1** | Filter cutoff | Filter resonance | Legacy sub bass |
| **SU.2** | Filter cutoff | Unison | Fat detuned bass |
| **SU.3** | Filter cutoff | Filter resonance | Filtered lead |
| **SU.4** | Filter cutoff | PWM | Pulse-width lead |
| **SU.5** | Tone | Length | Stab / pluck |
| **SU.6** | Length | Sweep | Sweeping lead |
| **SU.7** | Tune | Speed | Dub siren — sine |
| **SU.8** | Tune | Speed | Dub siren — square, octave |
| **SU.9** | Tune | Speed | Dub siren — sawtooth |

Full parameter pool across the engine: **age · filter cutoff · filter resonance · unison · tone · length · sweep · LFO speed · tune**.

### Playing Supertones

- Press **KEYS** to play the selected supertone chromatically across the pads (scale and key set in system settings, or hold **KEYS** + KNOB X / KNOB Y).
- Set play mode to **key** (Sound Edit → Sound Mode) for polyphonic chords, **legato** for mono glides.
- **Dub sirens (SU.7–SU.9)**: press and hold a pad and lean into it — pressure drives pitch and LFO depth. KNOB X retunes, KNOB Y sets sweep speed. Record the pad hits into a pattern like any other sound; pressure is captured with velocity enabled.
- Hold **TIMING** + multiple pads in keys mode for **arpeggio** (oneshot or legato sounds).
- Supertones respond to **velocity and aftertouch**, so pad velocity (system code 301 / 302) meaningfully changes the tone.

## Loops (LOP) — Live Remix Palette

New play mode alongside oneshot / key / legato. Set it in **Sound Edit → Sound Mode** with **KNOB X**.

- A LOP pad runs **continuously in the background on its own track**, tempo-synced, starting muted.
- **Tap** the pad to mute / unmute. **Press and hold** to preview the loop from its start.
- LOP pads in the same **mute group** choke each other — one loop at a time, ideal for A/B section switching.
- A LOP is temporarily ducked when a oneshot in the same mute group fires, and unmutes on the next half beat after that oneshot finishes.
- **Time stretch**: Sound Edit → Time page, KNOB X = BPM / BAR / reverse, KNOB Y = sample tempo or bar length. Resampled patterns save as loops with BPM metadata automatically.
- **Loop Startup State (LSS)**: hold the current **group** button + **RECORD** for 2 s until `LSS` flashes, then `SAV`. Stores the muted/unmuted state of every LOP pad into the current pattern.

## Live State

Enter with **SOUND + MAIN** pressed together.

- **Vinyl tempo** — changing TEMPO here slows/speeds samples like a turntable *without* changing the project's global BPM.
- **Button lockout** — disable any control that could wreck a set. Configure under **SHIFT + ERASE** → `LIV`, or directly with system codes 900–938.

## Sampling Workflow

1. Press **[SAMPLE]** — all pads blink, ready to record.
2. Press **−** / **+** to select source: MIC, IN (line mono/stereo), RSP (resample), L.IN, R.IN, USB.
3. **KNOB X** = input level, **KNOB Y** = threshold (auto-trigger).
4. Hold a **pad** to record; release to stop. Press the pad to audition. **[SAMPLE]** or **[MAIN]** to exit.

**Hands-free**: hold **SHIFT** + press a pad to latch, then **PLAY** to record a pattern's length.

**Resample**: source = RSP, latch a pad on an empty group, hit play — bounces your beat into one sample (saved as a loop with BPM).

**Chop (SHIFT + SAMPLE)**: equal-length auto-chop (perfect even slices for loops), attack auto-chop (transient/loudest-part detection for percussion), or live chop (tap pads while the sample plays). Refine in/out with **KNOB X** / **KNOB Y**.

**Detect tempo of incoming audio**: hold **SAMPLE + TEMPO**.

## Sound Edit Pages (SHIFT + SOUND)

Page with **−** / **+**. Hold **SHIFT + SOUND** for 2 s to save.

| Page | KNOB X | KNOB Y |
|---|---|---|
| **Sound Mode** | Play mode: oneshot / key / legato / **loop** | Pan |
| **Trim** | Start point | Length / end point |
| **Supertone** | Preset parameter 1 | Preset parameter 2 |
| **Envelope** | Attack | Release |
| **Time** | Stretch mode: BPM / BAR / **rev** (reverse) | Sample BPM or bar division |
| **MIDI** | MIDI channel (1–16) | MIDI root note |
| **Mute Group** | Select pads that choke each other | — |

**Play modes**: *oneshot* = mono, plays the whole sample one at a time · *key* = polyphonic · *legato* = mono with pitch continuation · *loop* = background tempo-synced loop (LOP).

## Key Shortcuts & Shift Combos

| Action | Result |
|---|---|
| **SOUND** | Sound mode — browse / assign samples (− / + to change, SHIFT + − / + jumps by 10) |
| **Hold SOUND + numpad** | Type a sound number directly |
| **Hold SOUND + dot** | **Supertone selection** (then pads 0–9) |
| **SHIFT + SOUND** | Sound Edit (7 pages) |
| **SOUND + MAIN** | **Live state** |
| **MAIN** | Home — sequencer, scenes, patterns |
| **Hold MAIN + − / +** | Select scene |
| **Hold MAIN + numpad 1–9** | Change project (or scene, with Quick Select on) |
| **Hold MAIN + dot** | Override Quick Select to change project |
| **Hold MAIN + ENTER** | **Song mode** |
| **SHIFT + MAIN** | Commit scene (duplicate & save, move to next) |
| **Hold group + − / +** | Select pattern |
| **Hold group + numpad 1–9** | Quick Select pattern |
| **SHIFT + group 1** | Find next empty pattern (in song mode: add scene to list) |
| **SHIFT + group 2** | Undo |
| **SHIFT + group 3** | Copy (once = bar, twice = pattern; in song mode: cut scene) |
| **SHIFT + group 4** | Paste (in song mode: insert scene) |
| **TEMPO** | BPM (KNOB X, 40–399), metronome level (KNOB Y) |
| **Hold TEMPO + numpad** | Type a BPM (use dot for decimals) |
| **Hold MAIN + TEMPO** | Time signature |
| **Hold SAMPLE + TEMPO** | Detect tempo of incoming audio |
| **SHIFT + TEMPO** | Loop roll — KNOB X = length, KNOB Y = slide. TEMPO exits now, MAIN exits on next bar |
| **FX** | Select send FX for current group |
| **SHIFT + FX** | Master compressor / sidechain |
| **SAMPLE** | Sampling mode |
| **SHIFT + SAMPLE** | Chop mode |
| **KEYS** | Chromatic keyboard for selected pad |
| **Hold KEYS + KNOB X / Y** | Scale / key select |
| **TIMING** | Note interval (KNOB X), swing (KNOB Y) |
| **SHIFT + TIMING** | Timing correct (per-pad quantize, note offset) |
| **SHIFT + ERASE** | System settings |
| **Hold ERASE + pad** | Erase that pad's notes |
| **SHIFT + FADER** | Reset fader position |
| **SHIFT + PLAY** | Play from start |
| **RECORD then PLAY** | Record with 4-beat count-in |
| **RECORD + PLAY together** | Record with no count-in |
| **Hold RECORD + − / +** | Set pattern length (1–99 bars) |
| **Hold RECORD + pad** | Step-record a note |
| **Hold RECORD + FADER** | Record fader automation |
| **Hold group + RECORD (2 s)** | Save Loop Startup State (`LSS` → `SAV`) |
| **Hold TIMING + pad** | Note repeat (pressure-sensitive) |
| **TIMING then SHIFT + pad** | Latched note repeat |
| **Hold FX + pads** | Punch-In FX (pressure-sensitive, combinable) |
| **Hold FX + group button** | Solo group |
| **Hold SHIFT + knob** | Fine adjustment |

## Fader Assignments

Hold **FADER** + press a pad to assign: Level (default) · Pan · FX Send · Pitch · Attack · Release · Filter Cutoff · Filter Resonance

## Send FX (7 types)

| Effect | KNOB X | KNOB Y |
|---|---|---|
| **Delay** | Length (time between repeats) | Feedback (number of repeats) |
| **Reverb** | Length (room size) | Colour (dark / bright) |
| **Distortion** | Drive (overdrive amount) | Colour (filtering) |
| **Chorus** | Modulation (rate) | Feedback (prominence) |
| **Phaser** *(new)* | Modulation (rate) | Feedback (prominence) |
| **Filter** | Cutoff | Resonance |
| **Compressor** | Drive (input level) | Speed (squash rate) |

**Master output (SHIFT + FX)**: compressor — KNOB X = drive, KNOB Y = speed. **Sidechain**: select source sound and destination groups with the pads, KNOB X = duck length, KNOB Y = duck shape.

## Punch-In FX 2.0

Hold **FX** + press pads. Pressure-sensitive, combinable (e.g. LPF + HPF = band-pass), and recordable into the sequencer.

| Pad | Effect | Pressure control |
|---|---|---|
| 0 | Pitch Randomiser | Decreasing pitch |
| ENTER | Granuliser | Grain size |
| 1 | Beat Repeat | Beat length |
| 2 | Tape Stop | Slow down |
| 3 | Filter LFO | LFO speed |
| 4 | Low-Pass Filter | Cutoff |
| 5 | High-Pass Filter | Cutoff |
| 6 | Send FX | FX depth |
| 7 | **Stutter** | Stutter rate |
| 8 | **Octave Down** | Increasing pitch |
| 9 | **Bit Crush** | Bit / sample reduction |
| . (dot) | Sample Swap | — |

Pads 7–9 are the loop-optimised versions on Riddim; TE publishes the punch-in set as 12 effects but does not enumerate every pad in the online guide, so the remaining assignments follow the shared K.O. II layout.

## Note Intervals (TIMING + KNOB X)

1/1 · 1/2 · 1/4 · 1/8 · 1/8T · 1/16 · 1/16T · 1/32 — "T" = triplet. Swing (KNOB Y) applies to 1/8 and 1/16.

## Scales (Keys Mode)

12-tone equal temperament (default) · Major (Ionian) · Minor (Aeolian) · Dorian · Phrygian · Lydian · Mixolydian · Locrian · Major Pentatonic · Minor Pentatonic · Blues · Harmonic Minor · Melodic Minor. Key: C through B.

## Connectivity

- **LINE IN (3.5 mm)** — stereo, 24-bit, SNR 96 dBA, 6.5 kΩ, 0–12 dB analog gain, max 8 dBu / 2.0 Vrms
- **LINE OUT (3.5 mm)** — stereo / headphones, 24-bit, SNR 98 dBA, max 5 dBu / 1.4 Vrms
- **SYNC IN / OUT** — TIP = 8th, 16th or 24 PPQN; RING = start/stop; 3.3 V (in tolerates max 10 V)
- **MIDI IN / OUT** — 3.5 mm TRS Type A, MMA-compliant; IN opto-coupled, OUT 3.3 V
- **USB-C** — class-compliant MIDI + USB audio (OS 2.5), clock & transport, firmware update, sample transfer, 5 V / min 1 A power
- **Built-in mic** and **speaker** — mono
- **EP-2350 "ting"** (bundled) — handheld FX mic: echo, spring, pixie, robot + 4 onboard samples, modulation lever, 3.5 mm line out. Feed it into LINE IN and sample it.

## Specs at a Glance

| Spec | Value |
|---|---|
| Sample memory | 128 MB (all user-available) |
| Sample slots | 999 |
| Polyphony | 16 mono / 12 stereo voices |
| Sampling rate | 46,875 Hz / 16-bit (selectable 26,250 / 32,000 / 46,875) |
| Max mono sample | 40 s (OS 2.5) |
| Synth | Supertone subtractive, 10 slots (SU.0–SU.9) incl. dub sirens |
| Sound library | 400+ sounds, 13 contributing artists, 8 remixable artist tracks |
| Groups × pads | 4 × 12 |
| Patterns per group | 99 (up to 99 bars) |
| Scenes per project | 99 |
| Projects | 9 |
| Sequencer | 96 PPQN |
| Effects | 7 send FX + 12 Punch-In FX 2.0 + master compressor & sidechain |
| Tempo range | 40–399 BPM |
| Power | 4× AAA batteries or USB-C (5 V / min 1 A) |
| Dimensions | 240 × 176 × 16 mm |
| Weight | ~750 g (retailer listings) |

## Quick Tips

- Organise groups by role — drums in 1, bass in 2, melody/supertone in 3, loops in 4 — then Live State becomes a real mixer.
- Resample a 2-bar groove onto an empty pad; it lands as a **LOP** with BPM already tagged, ready to mute/unmute live.
- Put all your LOP pads in one **mute group** so only one section plays at a time, and leave your drums outside it.
- **Commit often** (SHIFT + MAIN) — it duplicates the scene so you can evolve an arrangement without losing your place.
- Dub siren over a live vocal: set SU.7–SU.9 on a pad, ride pressure with one hand and KNOB Y (speed) with the other, with delay send cranked.
- Save an **LSS** after you get a good mute combination — otherwise the pattern recalls the previous startup state.
- Set a pad's sample to `000` in Sound mode for a silent MIDI-only pad that consumes no voice.
- Sampling at 26,250 Hz (code 500) is a fast route to authentic lo-fi dub texture, not just a memory saver.
- Hold **SHIFT** while turning knobs or the fader for fine adjustment.
- Live input FX: plug into LINE IN, press MAIN, raise KNOB Y (send level) to run external audio through the selected effect.

---

# MIDI Implementation

## Note Number → Pad Map (48 pads)

| Note Range | Group | Pads (left→right, bottom→top) |
|---|---|---|
| 36–47 (C2–B2) | Group 1 | . 0 ENT 1 2 3 4 5 6 7 8 9 |
| 48–59 (C3–B3) | Group 2 | . 0 ENT 1 2 3 4 5 6 7 8 9 |
| 60–71 (C4–B4) | Group 3 | . 0 ENT 1 2 3 4 5 6 7 8 9 |
| 72–83 (C5–B5) | Group 4 | . 0 ENT 1 2 3 4 5 6 7 8 9 |

In **keys mode** the selected pad (sample or supertone) responds chromatically across the full 0–127 range.

## MIDI Implementation Chart

| Function | Transmitted | Recognized |
|---|---|---|
| **Basic channel (default)** | 1 | All (omni) |
| **Basic channel (changed)** | 1–16 | 1–16 |
| **Mode (default)** | Mode 1 (Omni on, Poly) | Mode 1 |
| **Mode (messages)** | x | x |
| **Note number (pads)** | 36–83 (C2–B5) | 36–83 |
| **Note number (keys mode)** | 0–127 | 0–127 |
| **Velocity (Note on)** | o | o |
| **Velocity (Note off)** | x | x |
| **Aftertouch** | x | —¹ |
| **Pitch bend** | x | o |
| **Control change** | o | o |
| **Program change** | o (0–127) | o (0–127) |
| **System exclusive** | o (identity reply) | o (identity request, incl. over TRS in OS 2.5) |
| **Song position** | x | x |
| **Song select** | x | x |
| **Tune request** | x | x |
| **Clock (F8)** | o | o |
| **Start / Continue / Stop** | o | o |
| **All sound off (CC 120)** | o | o |
| **Reset all controllers (CC 121)** | o | o |
| **All notes off (CC 123)** | o | o |
| **Local on/off** | x | x |
| **Active sensing** | x | x |
| **System reset** | x | x |

¹ The pads are pressure-sensitive and Supertone responds to velocity *and* aftertouch internally, but TE does not document external channel/poly-pressure handling.

## MIDI CC Map

| CC | Parameter | Range | Notes |
|---|---|---|---|
| 1 | Vibrato | 0–127 | Mod wheel → vibrato depth |
| 12 | FX Knob X | 0–127 | X parameter of the active punch-in / send FX |
| 13 | FX Knob Y | 0–127 | Y parameter of the active punch-in / send FX |
| 64 | Sustain pedal | 0–127 | 0–63 off, 64–127 on; key & legato voices |
| 0 + 32 | Bank Select MSB + LSB | 0–16383 | Combine with Program Change to reach sounds 1–999 (0-based) |
| 120 | All sound off | — | Panic |
| 121 | Reset all controllers | — | Also fired automatically at stop with system code 141 |
| 123 | All notes off | — | Panic |

## System Settings — MIDI & Sync (SHIFT + ERASE)

| Code | Setting |
|---|---|
| **100** | MIDI clock off *(default)* |
| **101** | MIDI clock in (receive only) |
| **102** | MIDI clock out (send only) |
| **110** | Receive all channels, send on channel 1 *(default)* |
| **111–126** | Receive and send on MIDI channel 1–16 |
| **127** | Only send MIDI if a channel is assigned in Sound Edit |
| **130** | MIDI thru off |
| **131** | MIDI thru on (forwards MIDI in → out) |
| **140** | Do not reset MIDI controllers at stop *(default)* |
| **141** | Reset MIDI controllers at stop |
| **200** | Sync in rate 1/8 note |
| **201** | Sync in rate 1/16 note *(default)* |
| **202** | Sync in rate 24 PPQN |
| **210** | Sync out rate 1/8 note |
| **211** | Sync out rate 1/16 note *(default)* |
| **212** | Sync out rate 24 PPQN |

## System Settings — Pads, Sequencer & Sampling

| Code | Setting |
|---|---|
| **300 / 301 / 302** | Pad velocity off *(default)* / high (soft touch) / low (vigorous play) |
| **310–319** | Scale: 12-TET *(default)*, major, minor, Dorian, Phrygian, Lydian, Mixolydian, Locrian, major pentatonic, minor pentatonic |
| **320–331** | Scale key C *(default)* through B |
| **340 / 341** | Sample auditioning while tweaking values on / off |
| **400 / 401** | Metronome at record + play / at record only *(default)* |
| **410 / 411 / 412** | Scene change immediately *(default)* / at bar end / at pattern end |
| **420 / 421** | Quick Select off / on |
| **440 / 441** | Song loop off / on |
| **450 / 451** | Play from current bar / from pattern start |
| **500 / 501 / 502** | Sample rate 26,250 Hz / 32,000 Hz / 46,875 Hz *(default)* |
| **510 / 511** | USB audio input: sampler only *(default)* / sampler + live monitoring |

## System Settings — Live State Lockout

Enable with 90x, disable with 92x/93x:

| Enable | Disable | Control |
|---|---|---|
| 900 | 920 | Fader button |
| 901 | 921 | Keys button |
| 902 | 922 | Sound button |
| 903 | 923 | Main button |
| 904 | 924 | Tempo button |
| 905 | 925 | Sample button |
| 906 | 926 | Timing button |
| 907 | 927 | FX button |
| 908 | 928 | Erase button |
| 909 | 929 | Record button |
| 910 | 930 | Sound edit |
| 911 | 931 | Commit |
| 912 | 932 | Loop |
| 913 | 933 | Chop |
| 914 | 934 | Timing correct |
| 915 | 935 | Output |
| 916 | 936 | System |
| 917 | 937 | Fader |
| 918 | 938 | Metronome |

## Controlling Riddim from a MIDI Keyboard

1. Connect via TRS-to-MIDI (Type A) into MIDI IN, or USB-C.
2. Default is receive-on-all-channels (code 110) — any note you play triggers the mapped pad.
3. For chromatic play of one sound, put that pad in **keys mode** and set the pad's MIDI channel + root note in **Sound Edit → MIDI**.
4. Supertone pads respond to velocity; turn pad velocity on (code 301 / 302) to get the same response from the pads themselves.

## Sequencing External Gear

1. **SHIFT + SOUND** → page to the **MIDI** page.
2. **KNOB X** = MIDI channel the pad sends and receives on (1–16), **KNOB Y** = root note (match your sample's pitch).
3. Set the pad's sample to `000` in Sound mode for a silent MIDI-only trigger.
4. Set code **127** to send MIDI only from pads with an assigned channel, and **102** (or 101) for clock direction.
5. Record as usual — notes go out on the assigned channel, and fader automation stays internal.

USB-C is class-compliant MIDI. The TRS jacks are Type A (tip = current source, ring = current sink).

---
*Sources: teenage.engineering EP-40 guide (OS 2.5) — hardware, modes, buttons and combos, functions, effects, system, tech specs, how-to, what's new; teenagemanual.com EP-40 answers; spongefile.com "New features of the EP-40 Riddim"; midi.guide.*
