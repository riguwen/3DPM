# 3DPM Dataset

![RSS_Sample2](https://github.com/riguwen/3DPM/assets/102604584/f0d09d17-f0e0-4657-9245-3e6e5abf7137)

The 3-D Propagation Model (3DPM) comprises a small, ready-to-use dataset of multi-channel received signal strength within varying incident wave angles, tailored for few-shot learning applications.

## About Data collection methodology

The geometry-based line-of-sight synthetic dataset incorporates dynamic rotations, antenna impairments, polarization losses, and misalignments, facilitating node-to-node analysis.

### Description of the data

K"_X_" denotes the fading severity of _X_

```
3DPM/
  -Train/
    -K1
      -Theta0
        -RSS0
        -RSS1
        -...
    -K3
      -Theta0
        -RSS0
        -RSS1
        -...    
    -...
  -Evaluation/
    -K0
      -Theta0
        -RSS0
        -RSS1
        -...
    -K2
      -Theta0
        -RSS0
        -RSS1
        -...    
      -...
  -README.md

```

## Authors

* **Eray Guven, Gunes Karabulut Kurt** - (*Initial work* - [<_arXiV_>](https://arxiv.org/abs/2401.01504) )



