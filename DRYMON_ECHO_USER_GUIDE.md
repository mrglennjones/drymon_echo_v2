# DRYMON ECHO
## User Guide & Creative Manual

**Tape Saturation & Doubletracker Effect for KORG NTS-3 kaoss pad**

Version 2.2 | Created by Glenn Jones

---

## 📖 INTRODUCTION

**Drymon Echo** combines vintage tape saturation with a versatile doubletracker/delay engine, bringing the warmth and character of analog tape machines to your NTS-3 kaoss pad. From subtle chorus to wild flanging, slapback echoes to creative stereo effects - all with organic tape wobble and real-time touchpad control.

### What Makes It Special

- **Dual Tape Voices**: Classic soft-knee saturation or Cassette ALC compression
- **Continuous Lag Range**: -0.3ms to 500ms (flange through echo)
- **Organic Wobble**: Authentic tape flutter (10-30Hz) and wow (0.5-2Hz) modulation
- **Three Stereo Modes**: Sum (wide), Invert (through-zero), Bounce (ping-pong)
- **Live Performance Ready**: Real-time touchpad control with two modes
- **Professional Quality**: 32-bit float processing, 48kHz sample rate

---

## 🎛️ PARAMETERS

### 1. SAT (Saturation) • 0-100%

**What it does**: Controls tape drive, compression, and harmonic distortion

**How to use it**:
- **0-30%**: Subtle warmth and harmonics - perfect for adding analog character without obvious distortion
- **30-60%**: Compressed, tape-colored sound - adds punch and thickness
- **60-100%**: Heavy saturation - obvious distortion, great for lo-fi effects

**💡 Tip**: Start at 20-30% for most applications. Push higher for creative destruction.

---

### 2. TONE • 0-100%

**What it does**: Shapes the frequency response from dark and warm to bright and clear

**How to use it**:
- **0-40% (Dark)**: Rolled-off highs, vintage warmth - emulates old tape
- **40-60% (Neutral)**: Balanced response - let the saturation speak
- **60-100% (Bright)**: Enhanced clarity - cuts through the mix

**💡 Tip**: Use darker settings with high saturation for lo-fi vibes. Brighter settings work well with subtle saturation.

---

### 3. LAG (Lag Time) • 0-100%

**What it does**: Sets the delay time between original and doubled signal

**The Ranges**:

**FLANGE (0-10%)**: -0.3ms to 3ms
- Negative delay creates pre-echo flanging
- Subtle movement and thickness
- Works beautifully with Invert mode

**CHORUS (10-30%)**: 3ms to 50ms
- Classic chorus doubling
- Wide stereo image
- Sweet spot for most instruments

**SLAPBACK (30-60%)**: 50ms to 150ms
- Vintage rockabilly delay
- Percussive doubling
- Great on vocals and guitars

**ECHO (60-100%)**: 150ms to 500ms
- Long tape echoes
- Rhythmic delays
- Ambient textures

**💡 Tip**: The lag time responds non-linearly - you get fine control in the musically useful ranges.

---

### 4. BLEND • 0-100%

**What it does**: Mixes between dry (original) and wet (affected) signal

**How to use it**:
- **0%**: Completely dry - bypassed delay (saturation still active)
- **25-50%**: Subtle doubling - most natural for instruments
- **50-75%**: Balanced mix - obvious effect
- **75-100%**: Wet-heavy - creative/experimental

**💡 Tip**: With Touch Ctrl enabled, the X-axis of the touchpad controls blend in real-time!

---

### 5. WOBBLE • 0-100%

**What it does**: Adds tape flutter and wow modulation to the delay time

**How to use it**:
- **0%**: Rock-solid, no movement
- **15-30%**: Subtle vintage character - sounds like real tape
- **30-60%**: Obvious warble - creative movement
- **60-100%**: Extreme modulation - experimental/lo-fi

**The Science**: Wobble combines two LFO speeds:
- **Flutter**: 10-30Hz (fast vibrato)
- **Wow**: 0.5-2Hz (slow drift)
- **Depth**: Up to ±5ms pitch variation

**💡 Tip**: Even 20-30% wobble adds life to static delays. Push to 50%+ for instant cassette vibes.

---

### 6. TYPE • Sum / Invert / Bounce

**What it does**: Changes how the delayed signal is mixed with the original

#### **Sum/Classic** (Default)
- **Mixing**: Delayed signal added in-phase
- **Saturation**: Soft-knee tape saturation (2nd/3rd harmonics)
- **Sound**: Wide stereo doubling
- **Use for**: Chorus, slapback, most applications

#### **Invert/Classic**
- **Mixing**: Delayed signal phase-inverted (subtracted)
- **Saturation**: Same soft-knee saturation
- **Sound**: Through-zero flanging, phase cancellation
- **Use for**: Jet-plane flanging, dramatic sweeps, thin/hollow effects

#### **Bounce/Cassette**
- **Mixing**: Left delay → Right, Right delay → Left (ping-pong)
- **Saturation**: Cassette ALC compression (4:1 ratio)
- **Sound**: Stereo ping-pong with lo-fi character
- **Use for**: Wide stereo delays, lo-fi effects, cassette emulation

**💡 Tip**: Try Invert mode with short lag times (5-15%) and high wobble for classic through-zero flanging!

---

### 7. TOUCH • Off / On

**What it does**: Enables custom touchpad control mode

#### **Touch Off** (Default)
Hardware touchpad mappings:
- **X-axis**: Controls Lag Time (sweep from flange to echo)
- **Y-axis**: Controls Wobble (stable to warble)

**Use for**: Live exploration of the lag time range

#### **Touch On** (Custom Mode)
Software touchpad mappings:
- **X-axis**: Controls Blend (dry ← → wet)
- **Y-axis**: Controls Wobble (none ← → max)

**Use for**: Live mixing and adding movement on the fly

**💡 Tip**: Enable Touch mode for DJ-style wet/dry control during drops and builds!

---

## 🎯 PRESET LIBRARY

### 🎸 GUITAR PRESETS

#### "Vintage Chorus"
```
SAT:    20%  │ Gentle warmth
TONE:   45%  │ Slightly dark
LAG:    15%  │ Chorus range
BLEND:  60%  │ Obvious but not overwhelming
WOBBLE: 25%  │ Authentic movement
TYPE:   Sum/Classic
TOUCH:  Off
```
**Use on**: Clean guitars, keys, synth pads
**Sounds like**: Classic analog chorus pedal with tape character

---

#### "Surf Slapback"
```
SAT:    35%  │ Punchy compression
TONE:   65%  │ Bright and cutting
LAG:    40%  │ Fast slapback
BLEND:  40%  │ Dry-focused
WOBBLE: 10%  │ Minimal movement
TYPE:   Sum/Classic
TOUCH:  Off
```
**Use on**: Rockabilly guitars, surf rock, vintage vocals
**Sounds like**: 1950s tape echo machine

---

#### "Shoegaze Wash"
```
SAT:    45%  │ Compressed and warm
TONE:   40%  │ Dark and washy
LAG:    75%  │ Long echo
BLEND:  70%  │ Wet-heavy
WOBBLE: 40%  │ Lots of movement
TYPE:   Sum/Classic
TOUCH:  Off
```
**Use on**: Reverb-soaked guitars, ambient textures
**Sounds like**: Dreamy, atmospheric shoegaze tones

---

### 🎤 VOCAL PRESETS

#### "ADT Doubling"
```
SAT:    15%  │ Very subtle
TONE:   50%  │ Neutral
LAG:    25%  │ Chorus/doubling
BLEND:  45%  │ Balanced
WOBBLE: 20%  │ Slight variation
TYPE:   Sum/Classic
TOUCH:  Off
```
**Use on**: Lead vocals, backing vocals
**Sounds like**: Abbey Road ADT (Automatic Double Tracking)

---

#### "Tape Echo Vocal"
```
SAT:    30%  │ Tape warmth
TONE:   55%  │ Slightly bright
LAG:    65%  │ Rhythmic echo
BLEND:  50%  │ Equal mix
WOBBLE: 30%  │ Vintage character
TYPE:   Sum/Classic
TOUCH:  Off
```
**Use on**: Vocals, spoken word, rap
**Sounds like**: Classic tape delay à la Echoplex

---

### 🎹 SYNTH PRESETS

#### "Through-Zero Flange"
```
SAT:    10%  │ Clean
TONE:   55%  │ Clear
LAG:    5%   │ Flange territory
BLEND:  75%  │ Effect-heavy
WOBBLE: 45%  │ Dramatic movement
TYPE:   Invert/Classic
TOUCH:  Off  (or On for manual sweeps)
```
**Use on**: Synth leads, basses, drums
**Sounds like**: Jet-plane whoosh, dramatic flanging

---

#### "Stereo Bounce Delay"
```
SAT:    50%  │ Cassette-style
TONE:   35%  │ Dark and lo-fi
LAG:    50%  │ Slapback-to-echo
BLEND:  65%  │ Wet-focused
WOBBLE: 40%  │ Warped tape
TYPE:   Bounce/Cassette
TOUCH:  Off
```
**Use on**: Synth leads, keys, arpeggios
**Sounds like**: Stereo ping-pong through a worn cassette

---

#### "Minimal Techno Space"
```
SAT:    25%  │ Controlled warmth
TONE:   60%  │ Clear highs
LAG:    55%  │ Rhythmic delay
BLEND:  55%  │ Balanced
WOBBLE: 15%  │ Tight modulation
TYPE:   Sum/Classic
TOUCH:  On   (for performance control)
```
**Use on**: Techno hats, minimal percussion, synth stabs
**Sounds like**: Spacious minimal techno delay

---

### 🥁 DRUM PRESETS

#### "Snare Slapback"
```
SAT:    40%  │ Punchy
TONE:   70%  │ Bright snap
LAG:    38%  │ Quick slap
BLEND:  35%  │ Dry-focused
WOBBLE: 5%   │ Minimal
TYPE:   Sum/Classic
TOUCH:  Off
```
**Use on**: Snare drums, claps
**Sounds like**: Classic 80s gated reverb snare

---

#### "Flanged Cymbals"
```
SAT:    20%  │ Light saturation
TONE:   65%  │ Shimmering
LAG:    8%   │ Short flange
BLEND:  60%  │ Obvious effect
WOBBLE: 35%  │ Movement
TYPE:   Invert/Classic
TOUCH:  Off
```
**Use on**: Cymbals, hi-hats, percussion
**Sounds like**: Swirling metallic textures

---

### 🎚️ PERFORMANCE PRESETS

#### "Live Touchpad Control"
```
SAT:    30%  │ Warm but clear
TONE:   50%  │ Neutral
LAG:    20%  │ Chorus (starting point)
BLEND:  50%  │ Balanced (starting point)
WOBBLE: 30%  │ Good movement (starting point)
TYPE:   Sum/Classic
TOUCH:  On   ⭐ KEY SETTING
```
**How to perform**:
- **X-axis**: Sweep blend from dry to wet during drops
- **Y-axis**: Add wobble for buildups and tension

**Use for**: Live performance, DJ sets, dramatic transitions

---

#### "Freeze Pad"
```
SAT:    60%  │ Heavy saturation
TONE:   30%  │ Dark and murky
LAG:    85%  │ Long echo
BLEND:  85%  │ Very wet
WOBBLE: 50%  │ Maximum warble
TYPE:   Bounce/Cassette
TOUCH:  Off
```
**Use on**: Sustained notes, feedback, drones
**Sounds like**: Infinite degrading cassette loop

---

## 💡 CREATIVE TECHNIQUES

### Technique 1: "Negative Flanging"
Set LAG to 0-3% for negative delay times. The pre-echo creates unique phase relationships that can't be achieved with normal flanging.

**Try this**:
```
LAG: 2% | BLEND: 70% | WOBBLE: 35% | TYPE: Invert
```
Move the touchpad X-axis slowly while playing sustained notes.

---

### Technique 2: "Rhythmic Ping-Pong"
Use Bounce mode with medium-long delay times to create rhythmic stereo delays.

**Try this**:
```
LAG: 55% | BLEND: 60% | WOBBLE: 20% | TYPE: Bounce/Cassette
```
Play staccato notes - each delay bounces left-right with lo-fi character.

---

### Technique 3: "Tape Stop Automation"
Enable Touch mode and use the Y-axis to automate wobble in real-time.

**Try this**:
```
Set WOBBLE: 10% | TOUCH: On
```
During a sustained note, slide your finger up the Y-axis - the wobble increases, creating a tape-slowdown effect.

---

### Technique 4: "Through-Zero Sweeps"
Combine Invert mode with touchpad lag control for dramatic jet-plane sweeps.

**Try this**:
```
LAG: 15% | BLEND: 80% | TYPE: Invert | TOUCH: Off
```
Sweep the X-axis while playing chords - creates dramatic phase-cancelled sweeps.

---

### Technique 5: "Infinite Degradation"
Crank wet blend and wobble for a self-oscillating loop that degrades over time.

**Try this**:
```
SAT: 70% | LAG: 80% | BLEND: 95% | WOBBLE: 60%
```
Play a note and let it feed back - each repeat degrades like a worn cassette.

---

## 🔧 TECHNICAL SPECIFICATIONS

**Audio Processing**
- Sample Rate: 48kHz
- Bit Depth: 32-bit floating point
- Latency: <1ms
- Dynamic Range: >90dB

**Delay System**
- Maximum Delay: 500ms (24,000 samples)
- Interpolation: Linear fractional delay
- Memory: 192KB SDRAM

**Modulation**
- Flutter LFO: 10-30Hz (sine wave)
- Wow LFO: 0.5-2Hz (sine wave)
- Max Deviation: ±5ms
- Modulation Type: Delay time modulation

**Saturation**
- Classic Voice: Soft-knee tape saturation (2nd/3rd harmonics)
- Cassette Voice: 4:1 ALC compression with gentle clipping
- Drive Range: 1-10x (Classic), 1-3x (Cassette)

**CPU Usage**
- Typical: 10-15%
- Maximum: 18%

**Code Stats**
- Total Lines: ~450
- Languages: C++ (unit.cc), C (header.c)
- Compiler: ARM GCC (EABI5)

---

## 📱 INSTALLATION

### Requirements
- KORG NTS-3 kaoss pad
- KORG KONTROL Editor (Windows/Mac)
- USB connection

### Steps
1. Download `drymon_echo.nts3unit` file
2. Open KORG KONTROL Editor
3. Connect NTS-3 via USB
4. Select your NTS-3 device
5. Drag `drymon_echo.nts3unit` into the effect slot
6. The unit will upload and appear as "Drymon Echo"

### Troubleshooting
- **"Wrong resolve symbol" error**: Make sure you have the latest version (v2.2)
- **Effect not appearing**: Power cycle the NTS-3
- **Kontrol won't connect**: Try a different USB cable

---

## 🎨 MIXING TIPS

### EQ Suggestions
- **Pre-effect**: Brighten sources going into Drymon Echo for clarity
- **Post-effect**: Cut low-mids if the saturation is adding too much warmth

### Compression
- Compressing *before* Drymon Echo keeps dynamics tight
- Compressing *after* can tame the saturation peaks

### Reverb
- Place reverb *after* Drymon Echo for spacious delays
- Use subtle reverb to blend the delay repeats

### Parallel Processing
If your setup allows parallel processing:
- Run Drymon Echo at 100% blend on a parallel channel
- Mix to taste with the dry signal
- Allows extreme settings without losing the dry clarity

---

## 🤝 GENRE-SPECIFIC GUIDES

### Rock & Indie
**Go-to settings**: Moderate SAT (30-40%), Chorus LAG (15-25%), TYPE: Sum
**Best for**: Guitars, vocals, drums
**Tip**: Use brighter TONE settings to cut through dense mixes

### Electronic & Techno
**Go-to settings**: Low SAT (10-25%), Variable LAG, TYPE: Bounce
**Best for**: Synths, percussion, rhythmic elements
**Tip**: Enable Touch mode for performance-ready wet/dry control

### Lo-Fi & Experimental
**Go-to settings**: High SAT (60%+), High WOBBLE (50%+), TYPE: Bounce/Cassette
**Best for**: Everything - go wild!
**Tip**: Extreme settings create instant degradation

### Jazz & Soul
**Go-to settings**: Low SAT (15-25%), Slapback LAG (35-45%), Low WOBBLE
**Best for**: Vocals, keys, horns
**Tip**: Keep it subtle - let the performance shine

### Hip-Hop & R&B
**Go-to settings**: Moderate SAT (30-40%), Echo LAG (60-80%), TYPE: Sum
**Best for**: Vocals, samples, drums
**Tip**: Rhythmic delays sync to tempo (adjust LAG manually)

---

## ❓ FAQ

**Q: Can I use this on the master bus?**
A: Yes, but keep saturation low (0-20%) to avoid over-processing. Great for adding subtle analog warmth.

**Q: Why does the effect sound different on different sources?**
A: Tape saturation responds to input level. Louder sources hit the saturation harder. This is authentic to real tape!

**Q: Can I sync the delay to tempo?**
A: The current version doesn't have automatic tempo sync, but you can manually set LAG to match your BPM.

**Q: What's the difference between Classic and Cassette saturation?**
A: Classic is smooth soft-knee saturation. Cassette adds 4:1 compression for a more aggressive, lo-fi character.

**Q: The touchpad isn't responding - what's wrong?**
A: Make sure TOUCH is set to On if you want custom X/Y control. With TOUCH Off, the hardware mappings are active.

**Q: Can I automate parameters via MIDI?**
A: NTS-3 parameter automation depends on your DAW setup. Check KORG's documentation for MIDI implementation.

---

## 🙏 CREDITS

**Created by**: Glenn Jones  
**Platform**: KORG NTS-3 kaoss pad  
**SDK**: logue-sdk  
**Version**: 2.2  
**License**: BSD 3-Clause

---

## 📝 VERSION HISTORY

**v2.2** (Current)
- Complete rewrite using proper NTS-3 SDK callbacks
- Fixed "Wrong resolve symbol" loading error
- Improved memory management with SDRAM allocation
- Added all required SDK functions (teardown, reset, resume, suspend, tempo)

**v2.1**
- Renamed to "Drymon Echo"
- Fixed parameter ranges (0-1023 compatibility)
- Updated header structure

**v2.0**
- Initial public release
- 7 parameters with touchpad control
- Dual saturation voices
- Three stereo modes

---

## 🎸 FINAL THOUGHTS

**Drymon Echo** is designed to be your go-to tape effect - from invisible analog warmth to extreme lo-fi destruction. The key is experimentation: every combination of parameters creates a different character.

Don't be afraid to push the controls to extremes. Some of the best sounds come from "wrong" settings.

Most importantly: **Have fun and make noise!** 🎵

---

**Questions? Feedback? Share your Drymon Echo creations!**

**Download the latest version**: [Include your download link]

---

*This user guide is part of the Drymon Echo v2.2 release*  
*© 2026 Glenn Jones | Free to use, modify, and distribute*
