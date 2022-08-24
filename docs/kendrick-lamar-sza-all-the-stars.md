---
template: overrides/blog.html
title: Kendrick Lamar, SZA - «All The Stars»
---

# Kendrick Lamar, SZA - «All The Stars»
[![Cover][1]][1]

  [1]: assets/images/chains/kendrick-lamar-sza-all-the-stars/cover.png

[«All The Stars»][31] has been engineered by [Matt Schaeffer][32]

  [31]: https://www.youtube.com/watch?v=JQbjS0_ZfJ0
  [32]: https://www.mattschaeffer.org/

## Vox-Lead
                 
### SSL Channel   

<figure>
  <img src="https://5-72.com/assets/images/chains/kendrick-lamar-sza-all-the-stars/sslchannel.png" width="400" />
</figure>

=== "Filters"

    ``` yaml
    High-pass: 102 Hz
    ```

=== "HF"

    ``` yaml
    Gain: 1.6db
    Freq: 11.57 kHz
    ```

=== "HMF"

    ``` yaml
    Gain: -3.0db
    Freq: 0.67 kHz
    Q: 1.76
    ```

=== "LMF"

    ``` yaml
    Gain: -2.9db
    Freq: 0.30 kHz
    Q: 2.50
    ```

=== "LF"

    ``` yaml
    Gain: -5.7db
    Freq: 50 Hz
    ```

=== "Dynamics"

    ``` yaml
    Compress: 3.1
    Release: 0.10 ms
    Threshold: -2.3db
    ```

### RCompressor

<figure>
  <img src="https://5-72.com/assets/images/chains/kendrick-lamar-sza-all-the-stars/rcompressor.png" width="450" />
</figure>

=== "Settings"

    ``` yaml
    Type: Manual, Electro, Smooth
    Attack: 5.41 ms
    Release: 70.0 ms
    Thresh: -15.8db
    Ratio: 3.18
    Gain: 2.0db
    ```

### Q10

<figure>
  <img src="https://5-72.com/assets/images/chains/kendrick-lamar-sza-all-the-stars/q10.png" width="450" />
</figure>

=== "Band-1"

    ``` yaml
    Band-type: High-pass
    Gain: -0.2db
    Freq: 49 Hz
    Q: 7.0
    ```

=== "Band-2"

    ``` yaml
    Band-type: High-pass
    Gain: -0.2db
    Freq: 48 Hz
    Q: 7.0
    ```

=== "Band-3"

    ``` yaml
    Band-type: High-pass
    Gain: 0.0db
    Freq: 50 Hz
    Q: 7.0
    ```

=== "Band-4"

    ``` yaml
    Gain: -2.4db
    Freq: 250 Hz
    Q: 7.0
    ```

=== "Band-5"

    ``` yaml
    Gain: -2.4db
    Freq: 630 Hz
    Q: 4.6
    ```

### DeEsser

<figure>
  <img src="https://5-72.com/assets/images/chains/kendrick-lamar-sza-all-the-stars/deesser.png" width="450" />
</figure>

=== "Settings"

    ``` yaml
    Frequency: 8191 Hz
    Threshold: -34.4db
    ```

### CLA-2A

<figure>
  <img src="https://5-72.com/assets/images/chains/kendrick-lamar-sza-all-the-stars/cla2a.png" width="600" />
</figure>

=== "Settings"

    ``` yaml
    Type: Limit
    Gain: 30.64
    Peak reduction: 60.04
    ```

### PuigTec EQP1A

<figure>
  <img src="https://5-72.com/assets/images/chains/kendrick-lamar-sza-all-the-stars/puigtecheqp1a.png" width="650" />
</figure>

=== "Settings"

    ``` yaml
    Boost: 3.2
    Atten: 1.5
    Low Freq: 100 Hz
    Bandwidth: 10.3
    Boost: 1.2
    Atten: 0
    High Freq: 16 kHz
    Atten sel: 10
    Main: Off
    ```

### Decapitator

<figure>
  <img src="https://5-72.com/assets/images/chains/kendrick-lamar-sza-all-the-stars/decapitator.png" width="600" />
</figure>

=== "Settings"

    ``` yaml
    Drive: 2.6
    Output: 6.3db
    ```

### FabFilter Pro-Q 2

<figure>
  <img src="https://5-72.com/assets/images/chains/kendrick-lamar-sza-all-the-stars/fabfilterproq2.png" width="650" />
</figure>

=== "Band-Purple"

    ``` yaml
    Freq: 4547.6 Hz
    Q: 1.000
    Gain: 0.0db
    ```

=== "Band-Blue"

    ``` yaml
    Freq: 8407.1 Hz
    Q: 5.454
    Gain: -6.98db
    ```

=== "Band-Green"

    ``` yaml
    Freq: 28114 Hz
    Q: 1.354
    Gain: +0.97db
    ```

[^1]:
    Always remember that these presets are not 100% suitable for your vocal abilities.
[^2]:
    This material has been published for informational purposes only.
