---
template: overrides/main.html
title: Zola Jesus - «Exhumed»
---

# Zola Jesus - «Exhumed»
[![Cover][1]][1]

  [1]: assets/images/chains/zola-jesus-exhumed/cover.jpg

[«Exhumed»][12] has been co-produced, engineered and mixed by [Alex DeGroot][11]
  [11]: https://alexdg.net/
  [12]: https://www.youtube.com/watch?v=lcJ4ECn8R7E
## Vox-Lead
### Hardware
[![Hardware][2]][2]

  [2]: assets/images/chains/zola-jesus-exhumed/bus/voxlead/hardware.jpg
!!! info "Vocal Chain" 
    Peluso P67 Microphone > Rupert Neve Designs 511 Preamp > Inward Connections The Brute Limiter > MOTU 16A Converter > Pro Tools > BF76 Compressor > EQ3 7-Band       

### RND 511 Preamp
!!! settings
    ``` markdown
    * Trim: -1.2dB
    * Gain 42dB
    * HPF: 84dB
    * Silk On, Texture set to Max
    ```

### Inward Connections Brute
!!! settings
    ``` markdown
    * Gain Reduction: 5.5dB
    * Output Level: 13dB
    * 250Hz HPF: On
    ```

### BF-76
[![BF-76][3]][3]

  [3]: assets/images/chains/zola-jesus-exhumed/bus/voxlead/bf-76.png
!!! settings
    ``` markdown
    * Input: ≈ -28dB
    * Output: -15dB
    * Attack set to slowest setting and Release set to fastest setting
    * Ratio: 4:1
    ```

### EQ3 7-Band
[![EQ3 7-Band][4]][4]

  [4]: assets/images/chains/zola-jesus-exhumed/bus/voxlead/eq3-7-band.png

!!! settings
    === "HPF"
        ``` markdown
        * Q: 6dB/oct
        * Freq: 125 Hz
        ```

    === "LPF"
        ``` markdown
        * Q: 6dB/oct
        * Freq: 8 kHz
        ```

    === "LF"
        ``` markdown
        * Q: 1.00
        * Freq: 311 Hz
        * Gain: -6dB
        ```

    === "LMF"
        ``` markdown
        * Q: 2.00
        * Freq: 600 Hz
        * Gain: -3dB
        ```

    === "MF"
        ``` markdown
        * Q: 1.00
        * Freq: 1.25 kHz 
        * Gain: -6dB
        ```

    === "HMF"
        ``` markdown
        * Q: 1.00
        * Freq: 2.24 kHz
        * Gain: -6dB
        ```

    === "HF"
        ``` markdown
        * Q: 1.00
        * Freq: 6 kHz 
        * Gain: -9dB
        ```

## Vocal Reverb Chain:
!!! info
    Aux Send on Lead Vocal track (set to +1.5dB) > Vocal Reverb Aux Channel > EQ3 7-Band > Native Instruments RC48 Reverb > EQ3 7-Band

### EQ3 7-Band (Pre Reverb)
[![EQ3 7-Band (Pre Reverb)][5]][5]

  [5]: assets/images/chains/zola-jesus-exhumed/bus/voxlead/eq3-7-band-pre-verb.png
!!! settings
    ``` markdown
    HPF: 
    * Q: 6dB/oct
    * Freq: 400 Hz

    LPF:
    * Q: 6dB/oct
    * Freq: 3 kHz
    ```

### RC-48 Reverb
[![RC-48 Reverb][6]][6]

  [6]: assets/images/chains/zola-jesus-exhumed/bus/voxlead/rc-48.png
!!! settings
    ``` markdown
    Large Church preset modified to have no Diffusion or Predelay
    ```

### EQ3 7-Band (Post Reverb)
[![EQ3 7-Band (Post Reverb)][7]][7]

  [7]: assets/images/chains/zola-jesus-exhumed/bus/voxlead/eq-7-band-post-verb.png
!!! settings
    === "HPF" 
        ``` markdown
        * Q: 6dB/oct
        * Freq: 100 Hz
        ```

    === "LPF"
        ``` markdown
        * Q: 6dB/oct
        * Freq: 5 kHz
        ```

    === "LF"
        ``` markdown
        * Q: 1.00
        * Freq: 350 Hz
        * Gain: -7.5dB
        ```

    === "LMF"
        ``` markdown
        * Q: 1.00
        * Freq: 855.6 Hz
        * Gain: -3dB
        ```

    === "MF"
        ``` markdown
        * Q: 1.00
        * Freq: 1.33 kHz 
        * Gain: -6dB
        ```

    === "HMF"
        ``` markdown
        * Q: 10.00
        * Freq: 3 kHz
        * Gain: -3dB
        ```

    === "HF"
        ``` markdown
        * Q: 1.00
        * Freq: 3 kHz 
        * Gain: -3dB
        ```

## Vocal Echo Chain:
!!! info
    Aux Send on Lead Vocal track (Set to -15dB) > Vocal Echo Aux Channel > EQ3 7-Band > Soundtoys Echoboy

### EQ3 7-Band (Pre Reverb)
[![EQ3 7-Band (Pre Reverb)][8]][8]

  [8]: assets/images/chains/zola-jesus-exhumed/bus/voxlead/eq3-7-band-pre-verb2.png
!!! settings
    ``` markdown
    HPF: 
    * Q: 6dB/oct
    * Freq: 600 Hz 

    LPF: 
    * Q: 6dB/oct
    * Freq: 10 kHz
    ```

### Echoboy
[![Echoboy][9]][9]

  [9]: assets/images/chains/zola-jesus-exhumed/bus/voxlead/echoboy.png
!!! settings
    ``` markdown
    * Echo Time: 1/8 dot
    * Feedback: 0.40
    * Style: Studio Tape
    ```
!!! important
    The Vocal Echo channel was also feeding into the Vocal Reverb channel via a send set to 0dB

## Mix Bus Chain:
!!! info 
    MOTU 16A > Thermionic Culture Little Red Bustard 16 Channel Tube Summing Mixer > TK Audio BC501 Compressor > TK Audio TK-lizer 500 EQ > Apogee Rosetta 200 Converter

### Little Red Bustard
!!! settings
    ``` markdown
    * Air: 3
    * Attitude: 3
    * Gain: 0dB
    ```

### TK BC501
!!! settings
    ``` markdown
    * Threshold: -2dB
    * Make-up Gain: 6.5dB
    * Blend: 5.5
    * Ratio: 4:1
    * Attack: 10ms
    * Release: 50ms
    * HPF: Off
    ```

### TK-lizer
!!! settings
    ``` markdown
    M/S: On
    Mid Channel Settings:
    * HPF: 25Hz
    LF:
    * Shape: Bell
    * Gain: -1.5dB
    * Freq: 255 Hz
    MF: 
    * Gain: -2dB
    * Freq: 400Hz
    Side Channel Settings:
    * HPF: 100Hz
    ```

## + addition from Alex DeGroot
[![addition][10]][10]

  [10]: assets/images/chains/zola-jesus-exhumed/addition.jpg
!!! quote
    Oh, one other detail that maybe someone will find interesting: it was recorded in a rented house on the shore of Lake Superior in northern Minnesota in the middle of winter. It was a great environment for inspiration, but not very good for acoustics. The sound reflected off all the glass windows and the waves of the lake are audible in the background of some of the vocal tracks. I guess everything ended up sounding alright in the end though! Here's a picture of my gear set up in the space where we recorded.

[^1]:
    Always remember that these presets are not 100% suitable for your vocal abilities.
[^2]:
    This material has been published for informational purposes only.
