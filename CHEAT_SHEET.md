# DRYMON ECHO - Parameter Cheat Sheet

**Quick Reference Card** | v2.2 | Glenn Jones

---

## 🎛️ THE 7 CONTROLS

| # | PARAMETER | RANGE | WHAT IT DOES | SWEET SPOT |
|---|-----------|-------|--------------|------------|
| 1 | **SAT** | 0-100% | Tape drive & saturation | 20-40% |
| 2 | **TONE** | 0-100% | Dark ← → Bright | 45-55% |
| 3 | **LAG** | 0-100% | Delay time (see ranges below) | 15-25% |
| 4 | **BLEND** | 0-100% | Dry/wet mix | 40-60% |
| 5 | **WOBBLE** | 0-100% | Tape flutter & wow | 20-35% |
| 6 | **TYPE** | 0-2 | Sum/Invert/Bounce + Voice | Sum/Classic |
| 7 | **TOUCH** | Off/On | Touchpad control mode | Off |

---

## 📏 LAG TIME RANGES

| LAG % | EFFECT | DELAY TIME | USE FOR |
|-------|--------|------------|---------|
| **0-10%** | **FLANGE** | -0.3ms to 3ms | Swoosh, thickness, jet-plane |
| **10-30%** | **CHORUS** | 3ms to 50ms | Doubling, width, shimmer |
| **30-60%** | **SLAPBACK** | 50ms to 150ms | Rockabilly, vocals, punch |
| **60-100%** | **ECHO** | 150ms to 500ms | Rhythmic delays, ambience |

---

## 🔄 TYPE MODES

| MODE | STEREO | SATURATION | SOUND | BEST FOR |
|------|--------|------------|-------|----------|
| **Sum/Classic** | In-phase | Soft-knee tape | Wide doubling | Most uses |
| **Invert/Classic** | Phase-inverted | Soft-knee tape | Through-zero flange | Dramatic effects |
| **Bounce/Cassette** | Ping-pong | ALC compression | Lo-fi stereo | Creative delays |

---

## 🎮 TOUCHPAD MODES

### TOUCH: Off (Default)
- **X-axis** → LAG (Sweep flange to echo)
- **Y-axis** → WOBBLE (Add movement)

### TOUCH: On (Performance)
- **X-axis** → BLEND (Dry/wet control)
- **Y-axis** → WOBBLE (Add movement)

---

## ⚡ 5 INSTANT PRESETS

### 1. CLASSIC CHORUS
```
SAT: 20  TONE: 50  LAG: 15  BLEND: 60  WOBBLE: 25
TYPE: Sum/Classic  TOUCH: Off
```
**→ Vintage analog chorus**

### 2. SLAPBACK
```
SAT: 35  TONE: 65  LAG: 40  BLEND: 40  WOBBLE: 10
TYPE: Sum/Classic  TOUCH: Off
```
**→ 1950s rockabilly**

### 3. JET FLANGER
```
SAT: 10  TONE: 55  LAG: 5   BLEND: 75  WOBBLE: 45
TYPE: Invert/Classic  TOUCH: Off
```
**→ Through-zero whoosh**

### 4. TAPE ECHO
```
SAT: 45  TONE: 40  LAG: 75  BLEND: 50  WOBBLE: 30
TYPE: Sum/Classic  TOUCH: Off
```
**→ Vintage tape machine**

### 5. LO-FI BOUNCE
```
SAT: 60  TONE: 30  LAG: 50  BLEND: 70  WOBBLE: 50
TYPE: Bounce/Cassette  TOUCH: Off
```
**→ Degraded cassette**

---

## 💡 QUICK TIPS

**Subtle Warmth**: SAT 15-25%, LAG 20%, BLEND 40%  
**Extreme Lo-Fi**: SAT 70%+, WOBBLE 60%+, TYPE: Bounce/Cassette  
**Live Performance**: TOUCH: On (X=Blend, Y=Wobble)  
**Master Bus**: SAT 10-20%, LAG 0%, BLEND 30% (warmth only)

---

## 🎸 GENRE QUICK GUIDE

| GENRE | SAT | LAG | TYPE | WOBBLE |
|-------|-----|-----|------|--------|
| **Rock/Indie** | 30-40% | 15-25% | Sum | 20-30% |
| **Electronic** | 10-25% | Any | Bounce | 15-40% |
| **Lo-Fi** | 60%+ | 30-80% | Bounce/Cas | 50%+ |
| **Vocals** | 20-35% | 25-45% | Sum | 15-25% |
| **Jazz** | 15-25% | 35-45% | Sum | 10-20% |

---

## 🔧 TROUBLESHOOTING

| PROBLEM | SOLUTION |
|---------|----------|
| Loading error | Use v2.2 file |
| No sound | Check BLEND (set 40%+) |
| Too quiet | Increase SAT or BLEND |
| Too distorted | Lower SAT (try 20%) |
| Touchpad not working | Set TOUCH: On |
| Too much movement | Lower WOBBLE |

---

## 📥 INSTALLATION

1. Open KORG KONTROL Editor
2. Connect NTS-3
3. Drag `drymon_echo.nts3unit` to effect slot
4. Done!

---

**Full User Guide**: See `DRYMON_ECHO_USER_GUIDE.md`  
**Quick Start**: See `QUICK_START.md`

---

*Drymon Echo v2.2 | © 2026 Glenn Jones | BSD License*  
*Print this page for quick reference!*
