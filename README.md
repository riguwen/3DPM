# About Dataset

The 3-D Propagation Model comprises a small, ready-to-use dataset of multi-channel received signal strength within varying incident wave angles, tailored for few-shot learning applications.

## About Data collection methodology

The geometry-based line-of-sight synthetic dataset incorporates dynamic rotations, antenna impairments, polarization losses, and misalignments, facilitating node-to-node analysis.

### Description of the data

K"**x**" denotes the fading channel severity for **x**
**
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

* **Eray Guven, Gunes Karabulut Kurt** - *Initial work* - [<_arXiV_>](https://arxiv.org/abs/2401.01504)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


