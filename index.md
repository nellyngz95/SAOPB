---
layout: default
---
The perceptual quality of synthetic sound models remains a significant challenge for sound designers, primarily due to the lack of standardized objective evaluation methods and the limited availability of diverse synthetic samples. These limitations complicate the identification of perceptual deficiencies in synthesized audio. While classification models can effectively differentiate between real and synthetic sounds, gaining insight into the underlying decision-making process can reveal which acoustic features need refinement.

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Sound categories

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

| Sound category     | Feature 1    | Feature 2         | Feature 3        | Feature 4         | Feature 5          | Classification        |
|:-------------|:-------------------|:------------------|:------------------|:------------------|:------------------|:------------------|:---------------------------|
| Applause     | pitchsalience      | pitchconfidence   | attackstart       | dyncomplexity     | amplitude5        | Temporal+Spectral  |
| Applause     | pitchconfidence    | mfcc_3            | amplitude3        | frequency1        | mfcc_6            | Temporal+Spectral  |
| Church Bells | amplitude2         | amplitude4        | pitchsalience     | amplitude1        | maxtototal        | Temporal+Perceptual |
| Church Bells | pitchsalience      | spectralflux      | dyncomplexity     | crest             | mfcc_3            | Temporal+Perceptual |
| Bubbles      | logattacktime      | flatnesssfx       | mfcc_1            | ldb               | intensity         | Temporal+Spectral  |
| Bubbles      | crest              | effectiveduration | frequency1        | pitchconfidence   | attackstart       | Temporal+Perceptual+Spectral |
| Droplets     | loudness           | effectiveduration | ldb               | rms               | mfcc_1            | Temporal+Spectral  |
| Droplets     | loudness           | rms               | ldb               | median            | spectralflux      | Temporal+Spectral  |

# Optimization
 | Sound category   | Main feature     | Optimization 1                          | Optimization 2                                       | Optimization 3                                            | Optimization 4                                        |
|:-------------|:-------------------|:----------------------------------------|:----------------------------------------------------|:---------------------------------------------------------|:-----------------------------------------------------|
| Applause     | pitchsalience      | Eq and reverb                           | Distortion tone + audience factor + Distortion change of the knee | Change in the audience size, mix width. Plus distortion. | More Clapping rate, enthusiasm, compressor + distortion (change in the knee) |
| Applause     | pitchconfidence    | High frequencies, Reverb and bell pitch 3.81 | Distortion Bell pitch 3.81                          | Distortion + source + energy                             | Low pass filter + compressor                          |
| Church Bells | amplitude2         | Eq High band frequencies (600-1000) + Reverb (Small Impulse) | Change in centre frequency 1140 + Reverb (Small Impulse) | Opt1 + Distortion + source + energy                      | Opt 3 + High Frequencies                             |
| Church Bells | pitchsalience      | Surface wtness + Vicosity               | Compressor                                           | Compressor + Flow amount                                  | Distortion                                            |
| Bubbles      | logattacktime      | Eq and reverb                           | Distortion tone + audience factor + Distortion change of the knee | Change in the audience size, mix width. Plus distortion. | More Clapping rate, enthusiasm, compressor + distortion (change in the knee) |
| Bubbles      | crest              | High frequencies, Reverb and bell pitch 3.81 | Distortion Bell pitch 3.81                          | Distortion + source + energy                             | Low pass filter + compressor                          |
| Droplets     | loudness           | Eq High band frequencies (600-1000) + Reverb (Small Impulse) | Change in centre frequency 1140 + Reverb (Small Impulse) | Opt1 + Distortion + source + energy                      | Opt 3 + High Frequencies                             |
| Droplets     | loudness           | Surface wtness + Vicosity               | Compressor                                           | Compressor + Flow amount                                  | Distortion                                            |

# Analysis



* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four
### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)
