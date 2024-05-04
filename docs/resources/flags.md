# UTAU Flags Masterlist

## General

| Flag | Default Value | Range | Effect |
|-|-|-|-|
| g | 0 | -100~100 | Gender Factor / Formant Filter |
| t | 0 | -100~100 | Microtonal Pitch Adjustment in 10 cent increments <br> Note: Adjusts in 1 cent increments before v0.2.77 |
| Y | 100 | 0~100 | Noise Suppression |
| H | 0 | 0~99 | Low Pass Filter |
| h | 0 | 0~99 | |
| F | 3 | 0~?  | |
| L | ? | 0~?  | |

### Flags only available after UTAU v0.2.46 (Built-in Resampler)

| Flag | Default Value | Range | Effect |
|-|-|-|-|
| b | 0 | 0~100 | BRE after formant changes |
| C | 0 | 0~100 | Low Pass Filter that cuts high frequencies |
| c | 50 | 0~100 | C flag before formant changes |
| D | 0 | 0~100 | Low Pass Filter that cuts mid frequencies |
| E | 0 | 0~100 | Low Pass Filter that cuts low frequencies |
| P | 86 | 0~100 | Peak Compressor |
| W | ? | ? | Adds robotic sound |
| G | ? | ? | Regenerates the .frq of the current note |

Source[^1][^2]

[^1]: https://w.atwiki.jp/utaou/pages/41.html
[^2]: http://kenchan22.web.fc2.com/i/utauproperty/utauproperty.html

## Individual

### Moresampler

| Flag | Default Value | Range | Effect |
|-|-|-|-|
| Mt | 0 | -100~100 | Tension |
| Mb | 0 | -100~100 | Breathiness |
| Mo | 0 | -100~100 | Openness |
| Mr | 0 | -100~100 | Resonance |
| Md | 0 | -100~100 | Dryness |
| MC | 0 | 0~100 | Coarseness |
| MG | 0 | 0~100 | Growl |
| MD | 0 | 0~100 | Distortion |

Source[^3]

[^3]: https://web.archive.org/web/20181008050145/https://webhost.engr.illinois.edu/~khua5/index.php/moresampler/

### doppeltler

Supports g, B, N, P, T flags

| Flag | Default Value | Range | Effect |
|-|-|-|-|
| a | 100 | ? | High frequency emphasis rate of the noise component |
| R | 0 | -100~100 | Backwards. reverse front and back |
| S | 0 | -100~100 | number of threads |
| i | 0 | -100~100 | length of the rear fixed area (ms) |
| v | 0 | -100~100 | consonant velocity of the rear fixed area |

Source[^4]

[^4]: http://utau2008.xrea.jp/2020/engine/doppeltler_readme_en.txt
