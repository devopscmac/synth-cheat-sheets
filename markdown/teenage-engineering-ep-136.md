# Teenage Engineering EP-136 K.O. Sidekick — Cheat Sheet

*Two-channel stereo mixer, audio interface, and FX processor. 2× stereo inputs + aux, 6 performance FX, 3-band EQ per channel, per-channel compressor. USB-C audio interface (8-in/4-out) and MIDI control.*

## Hardware Overview

| Section | Controls |
|---|---|
| **Top jacks** | CH1 IN, CH2 IN (3.5 mm stereo), USB-C |
| **Bottom jacks** | AUX IN, MAIN OUT, CUE OUT (3.5 mm stereo) |
| **Channel 1** | Gain knob (push=compressor menu), EQ (High, Mid, Low), Cue button, FX button, Fader |
| **Channel 2** | Gain knob (push=compressor menu), EQ (High, Mid, Low), Cue button, FX button, Fader |
| **Center** | Color LCD screen, Mod stick (bend left/right), Force pad (pressure-sensitive), Select button |
| **Battery lid** | 2× AAA batteries; system button underneath |
| **Dimensions** | 240 × 88 × 16 mm, 300 g |

## Quick Start

1. **Power**: 2× AAA batteries or USB-C. No power switch — plug in to power on.
2. **Connect sources**: Plug stereo sources into CH1 IN and CH2 IN.
3. **Set levels**: Turn Gain knobs so signal sits in the sweet spot (green on screen).
4. **Adjust EQ**: High / Mid / Low knobs per channel.
5. **Mix**: Use faders to balance the two channels.
6. **Monitor**: Press Cue button on a channel to preview through CUE OUT.
7. **Listen**: MAIN OUT to speakers or headphones.

## Signal Flow

```text
CH1 IN → Gain → Comp → EQ → Fader → \
                                         MAIN → MAIN OUT
CH2 IN → Gain → Comp → EQ → Fader → /
         AUX → (additional input) → MAIN
CUE: press Cue button to send pre-fader/pre-FX signal to CUE OUT
MAIN CUE: hold both Cue buttons → sends main mix to CUE OUT
```

## Gain Knob Controls

| Action | Result |
|---|---|
| Turn Gain knob | Adjust input gain |
| Click (push) Gain knob | Enter compressor menu |
| Turn in compressor menu | Adjust compression amount |
| Hold Select + turn in compressor menu | Select compressor type (e.g. saturation style) |
| Hold Select + click Gain knob | Enter channel screen (gain/pan view) |
| Hold Select + turn in channel screen | Adjust pan |

## EQ (3-Band, per channel)

| Knob | Frequency | Range |
|---|---|---|
| High | High shelf | −∞ to +∞ |
| Mid | Peaking | −∞ to +∞ |
| Low | Low shelf | −∞ to +∞ |

EQ style configurable in System Settings: DJ (isolator-style), Studio (shelving), Parametric.

## Compressor (per channel)

- Click **Gain knob** to enter compressor menu
- Turn to adjust **compression amount**
- Hold **Select** + turn to choose **compressor type** (saturation/character variations)

## Cue Buttons

| Action | Result |
|---|---|
| Press Cue (ch 1 or 2) | Send channel audio to CUE OUT (pre-fader, pre-FX); BPM shown on screen |
| Hold both Cue buttons | Enable **Main Cue** — main mix sent to CUE OUT instead |
| Select + Cue | Enter **Tempo screen** — view/edit detected BPM per channel |
| Tap Cue in Tempo screen | Tap tempo to set BPM |
| Hold Cue in Tempo screen | Enable/disable tempo tracking per channel |

## Faders

- Each fader controls channel level to MAIN OUT (no positive gain, 0 at bottom).
- Hold **Select** + move fader to see exact numeric level.

## FX (6 types, one per channel)

Press **FX button** on a channel to enter FX edit. Hold **FX** + move **Mod stick** to change FX type.

| FX | Mod Stick (X) | Force Pad (pressure) | Tip |
|---|---|---|---|
| **Filter** | Cutoff frequency | Resonance (+noise) | Play like an instrument with both |
| **Delay** | Length (1/32 – 2/1) | Amount (wet/dry mix) | Hold pad + move stick for transient changes |
| **Tape** | Fast forward / rewind | Wow & flutter (wobble) | Great for transitions |
| **Loop** | Loop length | Engage (locks to nearest beat) | Stick + pad = temporary length change |
| **Tremolo** | Length (rate) | Amount (depth) | Beat-synced volume modulation |
| **Siren** | Tone/pitch | Engage + pitch | Move stick while engaged for scratch effects |

### FX Performance Controls

| Action | Result |
|---|---|
| Mod stick left/right | Modulate FX X parameter |
| Force pad (pressure) | Modulate FX Y parameter |
| **Select** while modulating | **Lock** current FX value |
| Mod stick or Force pad (locked) | Release lock |
| Hold **Select** + move stick/pad | **Record** FX motion sequence (loops on release) |
| Hold both **FX** buttons + mod | Modulate both FX simultaneously |
| **Select** + both **FX** buttons | **Serial FX mode** — master out → FX1 → FX2 |

## Tempo / Beat Sync

- Sidekick detects BPM from incoming audio per channel.
- Tempo screen: **Select + Cue** → tap Cue to set, hold Cue to enable tracking.
- FX sync to detected BPM (delay, loop, tremolo lock to beat).
- Hold one or both Cue buttons in Tempo screen to choose tempo source per FX.

## USB Audio Interface

- **8 channels in** / **4 channels out**, 48 kHz / 24-bit
- Class-compliant — no drivers needed
- Routes all inputs + mains to DAW
- Also powers the unit

## System Settings

Press **System button** under battery lid.

| Setting | Options |
|---|---|
| EQ mode | DJ (isolator), Studio (shelving), Parametric (peaking) |
| Fader curve | Linear, Log |
| Compressor type | Various saturation/compression characters |
| MIDI channel | 1–16 |
| MIDI note map | See below |
| Factory reset | Restore defaults |
| Firmware version | Display current version |

## MIDI CC Map

### Outgoing (controller mode)

| Control | CC Ch1 | CC Ch2 |
|---|---|---|
| Gain knob | 20 | 25 |
| Gain button (push) | 21 | 26 |
| Cue button | 3 | 52 |
| FX button | 14 | 15 |
| EQ High | 22 | 27 |
| EQ Mid | 23 | 28 |
| EQ Low | 24 | 29 |
| Fader | 7 | 9 |
| Force pad | 1 (Ch3) | |
| Mod stick | Pitch bend (Ch3) | |

CC2 variants (when holding Select) available for all controls.

### Incoming (remote control)

| Control | CC | Ch |
|---|---|---|
| Master Cue mode | 27 | 3 |
| Master FX mode | 28 | 3 |
| Cue enable | 3 | 1–2 |
| Fader | 7 | 1–2 |
| EQ High | 22 | 1–2 |
| EQ Mid | 23 | 1–2 |
| EQ Low | 24 | 1–2 |
| Gain | 20 | 1–2 |
| Pan | 10 | 1–2 |
| Compression | 12 | 1–2 |
| Saturation | 13 | 1–2 |
| FX amount | 1 | 1–2 |
| FX type | PC 1–6 | 1–2 |
| FX param | Pitch bend | 1–2 |
| Local control off | CC#122 | — |

## Setup Examples

### With EP-133 K.O. II (classic pairing)

- Snapped together via EP pegs
- KO2 MAIN OUT → Sidekick CH1 IN
- A second KO2 or source → CH2 IN
- CUE OUT → headphones for preview
- MAIN OUT → speakers

### Daisy-chain multiple Sidekicks

- Sidekick #1 MAIN OUT → Sidekick #2 AUX IN
- Expand to 4, 6, 8+ channels

### USB audio interface

- USB-C → computer
- Record CH1, CH2, AUX, and MAIN mix into DAW (4 stereo channels)

### Send/return with external FX

- CUE OUT → external pedal input
- Pedal output → AUX IN
- Use Cue to send channels to pedal, AUX brings processed signal back

## Specs

| Spec | Value |
|---|---|
| Audio processing | 48 kHz / 24-bit |
| Input impedance (CH1/CH2) | 10 kΩ |
| Input impedance (AUX) | 7 kΩ |
| Max input level | 8 dBu (2 Vrms) |
| Output SNR | 108 dBA (typical) |
| USB audio | 8ch in / 4ch out, class-compliant |
| Power | 2× AAA or USB-C (5V) |
| Weight | 300 g (10.6 oz) |
| Dimensions | 240 × 88 × 16 mm |

---
*Source: teenage.engineering guides (EP-136 v1.0.0)*
