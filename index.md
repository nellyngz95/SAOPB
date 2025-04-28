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
| Applause     | Pitch salience      | pitchconfidence   | Attack start       | Dynamic complexity     | Amplitude 5        | Temporal and spectral  |
| Applause     | Pitch confidence    | MFCC 3           | Amplitude 3        | Frequency 1        | MFCC 6           | Temporal and spectral  |
| Church Bells | Amplitude 2         | Amplitude 4       | Pitch salience     | Amplitude1        | Max to total        | Temporal and perceptual |
| Church Bells | Pitch salience      | Spectral flux      | Dynamic complexity     | Crest             | MFCC 3            | Temporal and perceptual |
| Bubbles      | Log attack time      | Spectral flatnesss | mfcc_1            | LDB               | Intensity         | Temporal and spectral  |
| Bubbles      | Crest              | Effective duration | frequency1        | pitchconfidence   | Attack start       | Temporal, perceptual and spectral |
| Droplets     | Loudness           | Effective duration | LDB              | RMS              | MFCC 1           | Temporal and spectral  |
| Droplets     | Loudness           | RMS          | LDB             | Median            | Spectral flux      | Temporal and spectral  |

# Optimization
For the optimization we provide  the whole list of both sound categories, top 5 important features and the optimization made for the subjective test. All the optimization parameters vary depending on the model used in the procedural audio online engine: 
| Class          | Optimization 1                                               | Optimization 2                                                       | Optimization 3                                                | Optimization 4                                                    |
|:---------------|:--------------------------------------------------------------|:---------------------------------------------------------------------|:---------------------------------------------------------------|:------------------------------------------------------------------|
| Applause       | EQ and reverb                                                  | Distortion tone, more audience factor and a distortion change of the knee     | Change in the audience size, mix width and  distortion.       | More clapping rate and enthusiasm. We use compressor  and distortion ( with a change in the knee) |
| Applause       | EQ (high pass filter), Reverb and bell pitch 3.81                  | Distortion Bell pitch 3.81                                             | Distortion  plus changes in the source  and energy                                   | Low pass filter and  compressor                                      |
| Church bells   | Eq High band frequencies (600-1000), reverb (Small Impulse)   | Change in centre frequency 1140, reverb (Small Impulse)              | Optimization 1, distortion, changes in the source and energy  parameters                           | Optimization 3 + High pass filter (EQ) Frequencies                                           |
| Church bells   | Surface wetness + Viscosity                                    | Compressor                                                            | Compressor + flow amount                                       | Distortion                                                        |
| Bubbles        | Eq and reverb                                                  | Distortion tone + audience factor + Distortion change of the knee     | Change in the audience size, mix width. Plus distortion.       | Changes on the clapping rate, enthusiasm. Use of the  compressor and distortion (change in the knee) |
| Bubbles        | High frequencies, Reverb and bell pitch 3.81                  | Distortion Bell pitch 3.81                                             | Distortion, changes in the  source and  energy  parameters                                  | Low pass filter  and compressor                                      |
| Droplets       | Eq High band frequencies (600-1000),  reverb (Small Impulse)   | Change in centre frequency 1140 . Reverb (Small Impulse)              | Optimization 1 + Distortion + source + energy                            | Optimization 3 and the EQ on high frequencies
| Droplets       | Surface wetness and viscocity changes                                    | Compressor                                                            | Compressor  and changes on the flow amount                                       | Distortion                                                        |

# Analysis
In this section you will find the samples used in the subjective evaluation for SAOP 

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
