---
layout: default
---

## Examples
In this page you will find the different examples and analysis of the best perceived optimization vs. the default synthetic sample and the recorded (ground truth sample).
![Procedural Audio Engine ](assets/img/Nemisindo.png)
The page of the procedural audio engine: [Nemisindo](https://nemisindo.com/). This engine gives the opportunity to create and mofidy the models in real time


### Rain
The rain model used in Nemisindo is a mix between additive, modal physically informed and physical modelling. 
- **Ground Truth**  
The recorded sample:
  ![Rain-GroundTruth](assets/img/RainGroundTruth.png)

- **Default (6KSFX)**  
The default model :
  ![Rain-Default](assets/img/RainDefault(6KSFX).png)

- **Optimization**  
The best perceived model according to our subjective evaluation. 
Post production effects used: **Compression.**
We modified the parameters available like: **Ambient noise: 0.15, splatter: 0.96  and droplets: 0.5**

  ![Rain-Optimization](assets/img/RainOptimization4.png)

### Comparison of the features.

### Fire
The fire model used in Nemisindo is a mix between additive, modal, subtractive and physically informed synthesis. 

- **Ground Truth**  
The recorded sample:
  ![Fire-GroundTruth](assets/img/FireGroundTruth.png)

- **Default (6KSFX)**  
The model without any post-production effect:
  ![Fire-Default](assets/img/FireDefault(6KSFX).png)

- **Optimization**  
The best perceived model according to our subjective evaluation. 
Post production effects used: **Compression and we added more lapping and crackling with the parameters available in the procedural audio engine.**
  ![Fire-Optimization](assets/img/FireOptimization4.png)

### Applause
The applause model used in Nemisindo is an additive synthesis model.It is inspired by the Andrew Farnell work. 
- **Ground Truth**  
The recorded sample:
  ![Applause-GroundTruth](assets/img/ApplauseGroundTruth.png)

- **Default (6KSFX)**  
The model without any post-production effect.
  ![Applause-Default](assets/img/ApplauseDefault(6KSFX).png)

- **Optimization**
The best perceived model according to our subjective evaluation. 
Post production effects used: **We modified the parameters of clapping rate and enthusiasm. We performed compression and distortion.**
  
  ![Applause-Optimization](assets/img/ApplauseOptimization4.png)
  
[back](./)
