# Teenage Engineering PO-33 K.O! — Cheat Sheet

*Micro sampler and sequencer, predecessor to the EP-133 K.O. II. 40 seconds sample memory, 8 melodic + 8 drum slots, 16 effects, 16-step sequencer with 16 patterns. Built-in mic, speaker, and LCD. Powered by 2× AAA batteries.*

## Hardware Layout

| Section | Controls |
|---|---|
| **Knobs** | Knob A (top-left), Knob B (top-right) |
| **Row 1 (top)** | SOUND, PATTERN, BPM, FX, RECORD |
| **Row 2 (middle)** | WRITE, PLAY, 1–8 (melodic voices) |
| **Row 3 (bottom)** | 9–16 (drum voices, also pattern select) |
| **Jacks (top edge)** | LINE IN (3.5 mm stereo), LINE OUT (3.5 mm stereo) |
| **Other** | LCD screen, built-in mic, built-in speaker, folding kickstand |

## Getting Started

- **Power**: 2× AAA batteries. Set clock with Knob A (hours) + Knob B (minutes). Press any key to confirm.
- **Auto-off**: 5 min idle (60 min if LINE IN cable is plugged in). Press any key to wake.
- **Volume**: Hold **BPM** + press keys 1–16 (higher number = louder). Be careful with headphones above level 5.
- **Battery status**: Hold **SOUND** + press **BPM** to cycle: bAt (%), rEC (recording seconds left), CPU (%), rEl (firmware), ULT (voltage).
- **Factory reset**: Hold **PATTERN + WRITE** while inserting batteries.

## Sound Slots

| Keys | Type | Behavior |
|---|---|---|
| 1–8 | Melodic | Each key plays the sample at a different pitch (minor scale, root on key 5) |
| 9–16 | Drum | Each key triggers a different slice of the sample (auto-sliced on recording) |

- Select a sound: hold **SOUND** + press 1–16. Red LED shows occupied slots, flashing = current.
- Play: press key directly.
- **4-voice polyphony** (shared across melodic + drum). Melodic voices take priority.

## Sampling

1. Hold **RECORD** + press a slot key (1–16) to start recording (built-in mic or LINE IN if plugged in).
2. Release the key to stop. Recording time shown on LCD.
3. **Melodic slots** (1–8): record the full sample, tuned chromatically across keys 1–8.
4. **Drum slots** (9–16): auto-sliced by transient detection across 16 keys.

Distortion tip: if recorded level is hot enough, the Volume parameter acts as distortion. Watch for `CLP` on the display.

## Sequencer

- **16 patterns** × **16 steps** each
- **Step record**: press **WRITE** to enter step mode → press step keys to place notes → press **PLAY** to hear.
- **Live record**: while a pattern plays, hold **WRITE** + press keys 1–16 to punch in notes (quantized).
- Copy a step: hold a step for ~1 sec (`CPy`), then press another step to paste.
- Hold a step + **Knob B**: adjust note length. Hold step + **Knob A**: adjust note/slice.
- Hold a step (drum) + **BPM**: set retrigger count (1/2/3/4/6/8 × flam).
- **Copy pattern**: hold **WRITE + PATTERN** + press destination (1–16).
- **Clear pattern**: hold **RECORD + PATTERN**.
- **Pattern chain**: hold **PATTERN** + press keys 1–16 in order (up to 128 steps). Press a key again to remove.

## Sound Edit Parameters

Press **FX** to cycle pages:

| Page | Display | Knob A | Knob B |
|---|---|---|---|
| Tone / Volume | `ton` | Pitch (transpose) | Volume |
| Filter | `FLt` | Low-pass / High-pass cutoff | Resonance |
| Trim | `tri` | Start point | Length (end point) |

- Hold **RECORD** + turn Knob A/B to **reset** the current parameter to default (`rSt`).
- In drum mode, trim adjusts the last-triggered slice.

## Effects (Hold FX + keys 1–15)

| Key | Effect | Key | Effect |
|---|---|---|---|
| 1 | Loop 16 (steps) | 9 | Stutter 4 |
| 2 | Loop 12 | 10 | Stutter 3 |
| 3 | Loop Short | 11 | Scratch |
| 4 | Loop Shorter | 12 | Scratch Fast |
| 5 | Unison | 13 | 6/8 Quantize |
| 6 | Unison Low | 14 | Retrigger Pattern |
| 7 | Octave Up | 15 | Reverse |
| 8 | Octave Down | 16 | Bypass (mute all FX) |

Effects are applied in real time. To **save** FX into a pattern, enable **WRITE** mode while holding **FX** + key. To clear saved FX, hold **FX** + key 16 while in WRITE mode.

## Parameter Locking

While a pattern plays, hold **WRITE** + turn **Knob A or B** to lock the current parameter values per step. Lockable per-step: pitch, volume, filter cutoff, resonance.

Works as motion sequencing — each step can have different locked values even if the same sound plays.

## Copying Sounds & Slices

| Action | Combo |
|---|---|
| Copy slot → slot | Hold **SOUND + WRITE** + press target slot (1–16) |
| Copy slice → slice | Hold **SOUND + WRITE** + press drum slot (9–16) + press slice key (1–16) |
| Melodic → drum | Copies entire trimmed sample, auto-sliced into 16 across drum keys |
| Drum → melodic | Copies the last-played slice as a melodic slot |
| Delete sound | Hold **RECORD** + press **SOUND** |
| Clear pattern | Hold **RECORD** + press **PATTERN** |

Copying never reduces available recording memory. Tone/filter settings are preserved independently when copying.

## Tempo & Swing

- Press **BPM** to toggle presets: HIP HOP (80), DISCO (120), TENCHO (140).
- Hold **BPM** + Knob B: fine-tune tempo (60–240 BPM).
- Hold **BPM** + Knob A: swing amount.

## Sync

Hold **RECORD** + **BPM** to cycle sync modes:

| Mode | Input | Output |
|---|---|---|
| SY0 | Stereo | Stereo (default) |
| SY1 | Stereo | Mono/Sync |
| SY2 | Sync | Stereo |
| SY3 | Sync | Mono/Sync |
| SY4 | Mono/Sync | Stereo |
| SY5 | Mono/Sync | Mono/Sync |

Sync signal is on the **left** channel, audio on the **right** (3.5 mm TRS). Connect LINE OUT of master → LINE IN of slave.

## Backup & Restore

**Backup**: LINE OUT → recorder. Press **WRITE + SOUND + PLAY** to transmit data. Record as stereo WAV at 16-bit, 44.1 kHz minimum.

**Restore**: LINE IN → source playback. Press **WRITE + SOUND + RECORD** to enter receive mode → play the backup (erases all current data).

## Lock Tab

Breaking the lock tab preserves the current state permanently. In locked mode: create patterns, adjust params, delete sounds — but no new sampling or factory reset.

To restore: temporarily remove batteries (state returns to freeze point). To permanently reverse: solder the two pads together.

## Alarm Clock

- Hold **SOUND + PATTERN** to set alarm. Knob A = hours, Knob B = minutes.
- Press a pattern key (1–16) to use that pattern as the alarm sound. Turn Knob A fully left (`OFF`) to disable.
- Stop alarm by pressing any key.

## Specs

| Spec | Value |
|---|---|
| Sample memory | 40 seconds |
| Sample slots | 16 (8 melodic + 8 drum) |
| Polyphony | 4 voices |
| Patterns | 16 (up to 16 steps each) |
| Pattern chain | Up to 128 patterns |
| Effects | 16 |
| Sampling rate | 16-bit, 44.1 kHz |
| Audio I/O | 3.5 mm stereo in/out |
| Built-in mic | Mono |
| Built-in speaker | Mono |
| Power | 2× AAA (lasts ~2 months) |
| Dimensions | 104 × 60 × 15 mm |
| Weight | 67 g (without batteries) |
| Sync | Audio pulse sync (L=Sync, R=Audio) |

## Quick Tips

- Melodic slots follow a natural minor scale. Root note on key 5. Transpose with FX → `ton` → Knob A.
- Copy a melodic sample into a drum slot for reliable 16-slice auto-division (better than transient detection for loops).
- Trim drum slices after copying to tighten the timing. Use the Level meter (display bars after stop) to watch levels.
- Set a step's note/slice before placing it by playing the desired sound first.
- Only 4 voices available — melodic notes take priority over drum voices when voice count is exceeded.
- `CPy` a step to copy its note/slice + length — useful for building patterns faster.
- For glitchy drum rolls: set retrigger (hold step + BPM) to 4, 6, or 8.
- Backup your sounds as WAV before experimenting with destructive edits.

---
*Source: teenage.engineering guides, brianhilmers.com PO-33 guide, cubeleco.blogspot.com hidden features*
