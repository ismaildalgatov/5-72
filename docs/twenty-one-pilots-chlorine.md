---
template: overrides/blog.html
title: Twenty One Pilots - «Chlorine»
---

# Twenty One Pilots - «Chlorine»
[![Cover][8]][8]

  [8]: assets/images/chains/004-twenty-one-pilots-chlorine/cover.png

[«Chlorine»][9] has been engineered by [Adam Hawkins][10].

  [9]: https://www.youtube.com/watch?v=eJnQBXmZ7Ek
  [10]: https://adamhawkins.com/

## Piano Loop

### TG12345

<figure>
  <img src="https://5-72.com/assets/images/chains/004-twenty-one-pilots-chlorine/bus/pianoloop/001-tg12345.png" width="600" />
</figure>

=== "Settings"

    ``` yaml
    Dynamics: Limiter
    Recovery: 9.2
    Treble-Freq: 1.5 kHz
    Treble-Gain: 4.0db
    Bass: 1.9db
    Spread: -1.5
    ```

### FabFilter Pro-Q2

<figure>
  <img src="https://5-72.com/assets/images/chains/004-twenty-one-pilots-chlorine/bus/pianoloop/002-fabfilterproq2.png" width="600" />
</figure>

=== "Band-Green"

    ``` yaml
    Freq: 96.632 Hz
    Q: 0.938
    ```

=== "Band-Purple"

    ``` yaml
    Freq: 203.63 Hz
    Q: 1.435
    Gain: +2.63db
    ```

=== "Band-Blue"

    ``` yaml
    Freq: 10087 Hz
    Q: 0.950
    ```

## Vox-Lead

!!! error "Warning"
    ``` sh
    Input Signal in FabFilter was around -20db
    Vocal has been pre-processed with micro-pitch for stereo-field
    ```

### FabFilter Pro-Q2

<figure>
  <img src="https://5-72.com/assets/images/chains/004-twenty-one-pilots-chlorine/bus/voxlead/001-fabfilterproq2.png" width="600" />
</figure>

=== "Band-Green"

    ``` yaml
    Freq: 153.73 Hz
    Q: 1.110
    ```

=== "Band-Blue"

    ``` yaml
    Freq: 232.4 Hz
    Q: 1.000
    Gain: -1.02db
    ```

=== "Band-Red"

    ``` yaml
    Freq: 6142.7 Hz
    Q: 0.369
    Gain: -0.39db
    ```

=== "Band-Purple"

    ``` yaml
    Freq: 8967.9 Hz
    Q: 1.994
    Gain: -0.80db
    ```

### Scheps 73

<figure>
  <img src="https://5-72.com/assets/images/chains/004-twenty-one-pilots-chlorine/bus/voxlead/002-scheps73.png" width="600" />
</figure>

=== "Settings"

    ``` yaml
    Pre-amp: -5db
    ```

### CLA-76

<figure>
  <img src="https://5-72.com/assets/images/chains/004-twenty-one-pilots-chlorine/bus/voxlead/003-cla76.png" width="600" />
</figure>

=== "Settings"

    ``` yaml
    Type: Blue 
    Input: -26.6db
    Output: -21db
    Attack: 3.88 ms
    Release: 5.66 ms
    Ratio: 12
    ```

### dbx-160

<figure>
  <img src="https://5-72.com/assets/images/chains/004-twenty-one-pilots-chlorine/bus/voxlead/004-dbx-160.png" width="600" />
</figure>

=== "Settings"

    ``` yaml
    Threshold: 0.791
    Compression: 2.94
    Output: 3.1db
    ```

### J37

<figure>
  <img src="https://5-72.com/assets/images/chains/004-twenty-one-pilots-chlorine/bus/voxlead/005-j37.png" width="600" />
</figure>

=== "Settings"

    ``` yaml
    Formula: 811
    Delay: 1/16 
    Delay Level: -17db
    Delay High-pass: 173.2 Hz
    Delay Low-pass: 2849 Hz
    ```

### RDeEsser

<figure>
  <img src="https://5-72.com/assets/images/chains/004-twenty-one-pilots-chlorine/bus/voxlead/006-rdeesser.png" width="600" />
</figure>

=== "Settings"

    ``` yaml
    Thresh: -30.5db
    ```

### F6-RTA

<figure>
  <img src="https://5-72.com/assets/images/chains/004-twenty-one-pilots-chlorine/bus/voxlead/007-F6-RTA.png" width="600" />
</figure>

=== "High-pass"

    ``` yaml
    Freq: 28 Hz
    Q: 12
    ```

=== "Band-1"

    ``` yaml
    Freq: 360Hz
    Q: 0.6
    Gain: 0.9 
    Range: -3.4
    Threshold: -24.6db
    Release: 160 ms
    ```

=== "Band-4"

    ``` yaml
    Freq: 2565 Hz
    Q: 0.5
    Range: -1.8
    Threshold: -13.5db
    Release: 5 ms
    ```
[^1]:
    Always remember that these presets are not 100% suitable for your vocal abilities.
[^2]:
    This material has been published for informational purposes only.
