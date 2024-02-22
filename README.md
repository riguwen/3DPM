# About Dataset

3-D Propagation Model is a multi-channel received signal strength within variaing incident wave angle dataset small dataset ready-to-use in few-shot learning applications. 
## About Data collection methodology

A geometry based line of sight synthetic and node to node dataset includes dynamic rotations, antenna impairment, polarization loss and misalignments.   
This description gives a detailed process on how the data was collected. It should describe the conditions under which the data was recorded and also the devices used to record the data.

### Description of the data

K"**x**" denotes the fading channel severity for **x
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


