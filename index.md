---
layout: default
---
The perceptual quality of synthetic sound models remains a significant challenge for sound designers, primarily due to the lack of standardized objective evaluation methods and the limited availability of diverse synthetic samples. These limitations complicate the identification of perceptual deficiencies in synthesized audio. While classification models can effectively differentiate between real and synthetic sounds, gaining insight into the underlying decision-making process can reveal which acoustic features need refinement.


# Sound categories
The SOAP paper was performed in 30 sound categories. All the synthetic models are listed [here](https://docs.google.com/spreadsheets/d/1KNiRQdd2AxuzoDDhtLKynx-YiRtXolz7Cmi_yLuYXLk/edit?usp=sharing). 

We retrieved the top 5 features after using the Bottleneck framework. All the top 5 features of the 30 categories can be found [here](https://docs.google.com/spreadsheets/d/1D9WmVtdcp3gVJVWvY20wZEMUg0LAxOCs-plfeZjsb-M/edit?usp=sharing). 

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
For the optimization, we provide the whole list of both sound categories, top 5 important features and the optimizations made for the subjective test. 
All the optimization parameters vary depending on the model used in the procedural audio online engine:[Nemisindo](https://www.nemisindo.com)


| Class          | Optimization 1                                                | Optimization 2                                                        | Optimization 3                                                     | Optimization 4                                                     |
|:---------------|:---------------------------------------------------------------|:----------------------------------------------------------------------|:-------------------------------------------------------------------|:-------------------------------------------------------------------|
| Applause       | EQ and reverb                                                   | Distortion tone, more audience factor, and a distortion change of the knee | Change in the audience size, mix width, and distortion             | More clapping rate and enthusiasm. Use of compressor and distortion (with a change in the knee) |
| Applause       | EQ (high pass filter), Reverb and bell pitch 3.81               | Distortion Bell pitch 3.81                                              | Distortion plus changes in the source and energy                   | Low pass filter and compressor                                     |
| Church Bells   | EQ High band frequencies (600-1000), Reverb (Small Impulse)     | Change in centre frequency 1140, Reverb (Small Impulse)                | Optimization 1, distortion, changes in the source and energy       | Optimization 3 plus High pass filter (EQ) on frequencies           |
| Church Bells   | Surface wetness and viscosity                                   | Compressor                                                             | Compressor plus flow amount                                        | Distortion                                                         |
| Bubbles        | EQ and reverb                                                    | Distortion tone, audience factor, and distortion change of the knee    | Change in audience size, mix width, and distortion                 | Changes in clapping rate and enthusiasm. Use of compressor and distortion (change in the knee) |
| Bubbles        | High frequencies, Reverb and bell pitch 3.81                    | Distortion Bell pitch 3.81                                              | Distortion plus changes in the source and energy                   | Low pass filter and compressor                                     |
| Droplets       | EQ High band frequencies (600-1000), Reverb (Small Impulse)     | Change in centre frequency 1140, Reverb (Small Impulse)                | Optimization 1 plus Distortion, source and energy                  | Optimization 3 plus EQ on high frequencies                         |
| Droplets       | Surface wetness and viscosity changes                           | Compressor                                                             | Compressor plus changes on the flow amount                         | Distortion                                                         |
[Link to the full list of optimizations ](https://docs.google.com/spreadsheets/d/1yg0VtcU-2Eo1-I1Io8vB-8VSBgrAsxN4SJoMKOjoBSE/edit?usp=sharing)

# Analysis
In this section you will find the samples used in the subjective evaluation for SAOP, 
[More statistics](./another-page.html).
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


[Link to other resources](./another-page.html).


