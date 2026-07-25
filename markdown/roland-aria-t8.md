# Roland AIRA Compact T-8 — Cheat Sheet

*Ultra-portable rhythm & bass machine. 6 drum tracks (TR-808/909/606) + TB-303 bass. ACB analog modeling, 64 patterns, 32 steps. Battery-powered (~4.5h).*

## Top Panel Layout

| Section | Controls |
|---|---|
| **Jacks** | SYNC IN/OUT, MIX IN, MIX OUT/HEADSET, USB-C, VOLUME knob |
| **Common** | 4-digit LED display, TEMPO/VALUE knob, SHIFT, PATTERN, PLAY, REC |
| **Bass Drum** | LEVEL knob, TUNE knob (press DECAY to toggle) |
| **Snare Drum** | LEVEL knob, TUNE knob (press DECAY to toggle) |
| **Tom / Hand Clap** | LEVEL knob, TUNE knob, HAND CLAP button, TOM button |
| **Hi-Hat** | LEVEL knob, DECAY knob, CLOSED HH button, OPEN HH button |
| **Bass (303)** | LEVEL, PITCH, DECAY, CUTOFF, RESO, ENV MOD knobs; KYBD button |
| **FX** | DELAY knob, REVERB knob, ACCENT button |
| **Step buttons** | 16 buttons — pattern/bank select, step input, rhythm/bass programming |

## Tracks

| Track | Source | Controls |
|---|---|---|
| Bass Drum | TR-808/909 | LEVEL, TUNE, DECAY |
| Snare Drum | TR-808/909 | LEVEL, TUNE, DECAY, SNAPPY |
| Hand Clap (or Noise Tom / High Tom) | TR-606 | LEVEL, TUNE (shared with TOM) |
| Tom (Low × 2, selectable) | TR-808 | LEVEL, TUNE (shared with CLAP) |
| Closed Hi-Hat | TR-808/909 | LEVEL, DECAY |
| Open Hi-Hat | TR-808/909 | LEVEL, DECAY (tempo-sync option) |
| Bass | TB-303 | LEVEL, PITCH, DECAY, CUTOFF, RESO, ENV MOD |

## Signal Flow

```text
Rhythm (BD/SD/CP/TOM/CH/OH) ─┐
                               ├→ Main Mix → Delay → Reverb → MIX OUT
Bass (TB-303) ────────────────┘       ↑
                                  Overdrive (global)
                                  Sidechain (triggered by selected drum)
```

## Rhythm Sequencer (TR-REC)

- 6 instrument tracks, up to 32 steps
- **Record**: press REC → press step buttons to place hits
- **Real-time**: press REC → press PLAY → tap instrument buttons
- **Sub steps**: hold instrument button + step button for 32nd/16th triplet notes
- **Probability**: STEP + TEMPO/VALUE knob per step
- **Last step**: SHIFT + D# (LAST) to set pattern length
- **Pattern shift**: instrument button + TEMPO/VALUE knob to shift timing
- **Step scale**: menu `rSCL` — 16th, 32nd, 8th triplet, 16th triplet
- **Fill**: SHIFT + F# (FILL TRG) — uses pattern set by SHIFT + G (FILL PTN)

### Step Functions

| SHIFT + | Function |
|---|---|
| C (EXIT) | Exit menu |
| C# (ENTER) | Confirm value |
| D (SHUFFLE) | Shuffle/swing amount |
| D# (LAST) | Set pattern length (last step) |
| E (STEP 1-16) | Edit steps 1–16 |
| F (STEP 17-32) | Edit steps 17–32 |
| F# (FILL TRG) | Trigger fill |
| G (FILL PTN) | Select fill pattern |
| G# (RANDOM RHYTHM) | Random rhythm pattern |
| A (RANDOM BASS) | Random bass pattern |
| A# (PTN CLEAR ALL) | Clear entire pattern |
| B (PTN CLEAR INST) | Clear selected instrument |
| C (DELAY) | Delay settings |
| OCT– (REVERB) | Reverb settings |
| OCT+ (MENU) | System menu |
| SLIDE (WRITE) | Save pattern |

## Bass Sequencer (TB-303)

- 1 bass track, up to 32 steps
- **KYBD**: press to enter keyboard mode → use step buttons to play notes
- **Accent**: press ACCENT button (while bass selected) → step buttons to toggle accent per step
- **Slide**: press step button while entering to create portamento between notes
- Input notes via step buttons in REC mode, or play live in KYBD mode
- Waveform select: SAW or SQUARE (menu `bLAv` or PATTERN + STEP 11)
- **Transpose**: BASS + KYBD + TEMPO/VALUE knob

## Effects

| Effect | Control | Details |
|---|---|---|
| **Delay** | DELAY knob, SHIFT + C | Syncs to tempo; send level; delay-to-reverb send |
| **Reverb** | REVERB knob, SHIFT + OCT– | Room/hall/plate; send level |
| **Overdrive** | Global, menu `OdOn`, `Oddr`, `OdLv` | Per-instrument on/off, global drive & level |
| **Sidechain** | Menu `SC`, `SCdG`, `SCti`, `SCSr` | Ducking or gating triggered by selected drum |

### Sidechain

- Menu `SC` sets depth & sustain length
- `SCdG` configures per-target (instrument/delay+reverb/USB): ducking (dv.1–50) or gating (Gt.1–50)
- `SCti` sets time ratio (0.5–2.0, 1.0 = 8th note)
- `SCSr` selects trigger source (BD, SD, CP, TOM, CH, OH)

## Instrument Menu (SHIFT + OCT+)

| Menu Item | Range | Description |
|---|---|---|
| NUtE (Mute) | On/Off per inst | Mute/unmute |
| GAIn | 0–200 | Per-instrument gain |
| tUnE | –128–127 | Per-instrument tuning |
| dECY | –128–127 | Per-instrument decay |
| PAn | L64–C0–R63 | Per-instrument pan |
| AtK | 0–255 | Bass drum attack |
| SnPy | 0–255 | Snare snappy/wire volume |
| CoIr | –128–127 | Tom noise/color |
| tON | tON1, tON2 | Tom sound selection |
| CLAP | CP/hnt/htON | Hand clap sound type |
| ƶtNp (OH Sync) | OFF, On | Open HH decay tempo-sync |
| ƼľAv (Bass Wave) | SAľ, Sqr | Bass waveform |
| ƐACC (Rhythm Accent) | OFF, 1–255 | Accent strength (rhythm) |
| ƼACC (Bass Accent) | OFF, 1–255 | Accent strength (bass) |
| ƳSyn (Pattern Sync) | OFF, OnCE, ALľy | Rhythm/bass sync mode |
| ƐSCL (Rhythm Scale) | 16, 32, 8-3, 16-3 | Step scale |
| ƼTRi (Bass Triplet) | OFF, On | Triplet grid |
| OƞOn (OD On) | OFF, On | Overdrive per instrument |
| Oƞdr (OD Drive) | 0–127 | Global overdrive gain |
| OƞLv (OD Level) | 0–127 | Overdrive level per inst |
| ƞSyn (Delay Sync) | OFF, On | Tempo-sync delay |
| ƞƐSE (Delay→Reverb) | 0–127 | Delay send to reverb |
| SC (Sidechain) | OFF, 1–100 | Sidechain depth/sustain |
| SŹdG (SC Duck/Gate) | dv.1–50, OFF, Gt.1–50 | Duck/gate per target |
| SŹti (SC Time Ratio) | 0.5–2.0 | Sidechain timing |
| SŹSr (SC Source) | BD, SD, CLAP, tON, CH, OH | Trigger source |
| ƭcLk (Sync Clock) | 1/2/3/4/6/8/12/24 | Clocks per beat |
| rƴCh (Rhythm MIDI Ch) | 1–16, OFF | Rhythm MIDI channel |
| bƟCh (Bass MIDI Ch) | 1–16, OFF | Bass MIDI channel |
| tXPc (TX PC) | OFF, On | Send PC on pattern change |
| rXPc (RX PC) | OFF, On | Receive PC to change pattern |
| Pc.Ch (PC Channel) | 1–16 | Program change channel |
| SYnC (Clock Sync) | AUTO, Int, NIdI, USB | Clock source |
| thrv (Thru) | OFF, On | MIDI thru |
| USƼd (USB Direct) | OFF, 1–127 | USB output level |
| ƷLnk (AIRA Link) | OFF, On | MX-1 link mode |
| LvŸC (Level Curve) | nrN, SPL | Level knob curve |
| rLod | — | Reload pattern |
| rLƞr | — | Reload rhythm |
| rLƞb | — | Reload bass |
| COPY | — | Copy pattern |
| CPƮr | — | Copy rhythm |
| CPƮb | — | Copy bass |

## Shortcuts

| Action | Result |
|---|---|
| PATTERN + STEP 1–4 | Select bank 1–4 |
| PATTERN + STEP 10 | Overdrive settings |
| PATTERN + STEP 11 | Bass waveform select |
| PATTERN + STEP 12 | Sidechain settings |
| PATTERN + STEP 14 | Reload rhythm |
| PATTERN + STEP 15 | Reload bass |
| PATTERN + STEP 16 | Reload all |
| PATTERN + TEMPO/VALUE | Master probability |
| Step button + TEMPO/VALUE | Per-step probability |
| Instrument button + step (in REC) | Sub step input |
| Instrument button + TEMPO/VALUE | Shift pattern timing |
| BASS + KYBD + TEMPO/VALUE | Transpose bass |
| SHIFT + instrument button | Quick mute |
| SHIFT + ACCENT (menu) | USB input as sidechain target |

## Connectivity

- **SYNC IN/OUT** — mini-jack sync with AIRA Compact, Pocket Operator, etc.
- **MIX IN** — blend external audio
- **MIX OUT/HEADSET** — stereo out / headphones
- **USB-C** — audio + MIDI + charging
- **MIDI IN/OUT** — TRS Type A

## Specs

| Spec | Value |
|---|---|
| Sound engine | ACB (Analog Circuit Behavior) |
| Drum sources | TR-808, TR-909, TR-606 |
| Bass source | TB-303 (saw/square wave) |
| Patterns | 64 (4 banks × 16), up to 32 steps |
| Tracks | 6 rhythm + 1 bass |
| Effects | Delay, Reverb, Overdrive, Sidechain |
| Battery | Li-ion, ~4.5 h use, ~3 h charge |
| Dimensions | 188 × 106 × 36 mm |
| Weight | 305 g |

## MIDI Implementation

### Channel Map

| Device | Default Ch |
|---|---|
| Rhythm (drums) | Ch 10 |
| Bass (303) | Ch 2 |
| Program change | Ch 16 |

### Note Number → Instrument Map

| Instrument | Tx Note | Rx Notes |
|---|---|---|
| Bass Drum | 36 | 35, 36 |
| Snare Drum | 38 | 38, 40 |
| Hand Clap | 50 | 48, 50 |
| Tom | 47 | 45, 47 |
| Closed Hi-Hat | 42 | 42, 44 |
| Open Hi-Hat | 46 | 46 |

Bass note range: 12–96 (C–1 to G7), same as received.

### MIDI Implementation Chart

| Function | Transmitted | Recognized |
|---|---|---|
| **Basic channel** | 2 (bass), 10 (rhythm), 16 (PC) | 2, 10, 16 |
| **Mode** | Mode 3 (Omni off, Poly) | Mode 3 |
| **Note number (bass)** | 12–96 | 12–96 |
| **Note number (rhythm)** | Per-instrument (see table) | 0–127 |
| **Velocity (Note on/off)** | o | o |
| **Aftertouch** | x | x |
| **Pitch bend** | x | x |
| **Control change** | x | x |
| **Program change** | o (0–63) | o (0–63) |
| **System exclusive** | x | x |
| **Clock (F8)** | o | o |
| **Start (FA)** | o | o |
| **Continue (FB)** | x | o |
| **Stop (FC)** | o | o |
| **All sound off (120)** | o | o |
| **All notes off (123)** | x | o |
| **Active sensing** | o | o |

### CC Parameters

T-8 does not transmit or receive control change messages (CC x). Parameter control is via Note On/Off velocity, Program Change, and System Real-Time messages only.

---
*Source: Roland official T-8 Owner's Manual (Version 1.02)*
