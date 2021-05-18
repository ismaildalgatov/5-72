---
template: overrides/main.html
title: Twenty One Pilots - «Chlorine»
---

# Twenty One Pilots - «Chlorine»

[![Cover][8]][8]

  [8]: assets/images/chains/twenty-one-pilots-chlorine/cover.jpg

«Chlorine» has been engineered by Adam Hawkins.

## PianoLoop

### TG-12345

[![TG-12345][10]][10]

  [10]: assets/images/chains/twenty-one-pilots-chlorine/bus/pianoloop/tg12345.png

!!! settings
``` markdown
Dynamics: Limiter
Recovery: 9.2
Treble-Freq: 1.5kHz
Treble-Gain: 4.0db
Bass: 1.9db
Spreed: -1.5
```
### Fabfilter Pro-Q2

[![Fabfilter Pro-Q2][9]][9]

  [9]: assets/images/chains/twenty-one-pilots-chlorine/bus/pianoloop/fabfilterproq2.png

!!! settings
_Band-Green_:
``` markdown
* Freq: 96.632Hz
* Q: 0.938
```
_Band-Purple_:
``` markdown
* Freq: 203.63Hz
* Q: +2.63db
* Gain: 1.435
```
_Band-Blue_:
``` markdown
* Freq: 10087Hz
* Q: 0.950
```
## Vox-Lead

!!! error "Warning"
    ``` sh
    Input Signal in Fabfilter was around -20db
    Vocal has been pre-processed with micro-pitch for stereo-field
    ```

### Fabfilter Pro-Q2

[![Fabfilter Pro-Q2][1]][1]

  [1]: assets/images/chains/twenty-one-pilots-chlorine/bus/voxlead/fabfilterproq2.png

!!! settings
_Band-Green_:
``` markdown
* Freq: 153.73Hz
* Q: 1.110
```
_Band-Blue_:
``` markdown
* Freq: 232.4Hz
* Q: 1.000
* Gain: -1.02db
```
_Band-Red_:
``` markdown
* Freq: 6142.7Hz
* Q: 0.369
* Gain: -0.39db
```
_Band-Purple_:
``` markdown
* Freq: 8967.9Hz
* Q: 1.994
* Gain: -0.80db
```

### Scheps 73

[![Scheps 73][2]][2]

  [2]: assets/images/chains/twenty-one-pilots-chlorine/bus/voxlead/scheps73.png

!!! settings
``` markdown
Pre-amp: +5db
```

### CLA-76

[![CLA-76][3]][3]

  [3]: assets/images/chains/twenty-one-pilots-chlorine/bus/voxlead/cla76.png

!!! settings
``` markdown
Type: Blue 
Input: -26.6db
Output: -21db
Attack: 3.88ms
Release: 5.66ms
Ratio: 12
```

### dbx-160

[![dbx-160][4]][4]

  [4]: assets/images/chains/twenty-one-pilots-chlorine/bus/voxlead/dbx-160.png

!!! settings
``` markdown
Threshold: 0.791
Compression: 2.94
Output: 3.1db
```

### J37

[![J37][5]][5]

  [5]: assets/images/chains/twenty-one-pilots-chlorine/bus/voxlead/j37.png

!!! settings
``` markdown
Formula: 811
Delay 1/16 
Delay Level: -17db
Delay High-pass: 173.2Hz
Delay Low-pass 2849kHz
```

### RDeEsser

[![RDeEsser][6]][6]

  [6]: assets/images/chains/twenty-one-pilots-chlorine/bus/voxlead/rdeesser.png

!!! settings
``` markdown
Thresh: -30.5db
```

### F6-RTA

[![F6-RTA][7]][7]

  [7]: assets/images/chains/twenty-one-pilots-chlorine/bus/voxlead/F6-RTA.png

!!! settings
_High-pass_:
``` markdown
* Freq: 28Hz
* Q: 12
```
_Band-1_:
``` markdown
* Freq: 360Hz
* Q: 0.6
* Gain: 0.9 
* Range: -3.4
* Threshold: -24.6db
* Release: 160ms
```
_Band-4_:
``` markdown
* Freq: 2565Hz
* Q: 0.5
* Range: -1.8
* Threshold: -13.5db
* Release: 5ms
```
[^1]:
    Always remember that these presets are not 100% suitable for your vocal abilities.
[^2]:
    This material has been published for informational purposes only.