# MetroGNN

# Installation 

### Environment
* **Tested OS: **Linux
* Python >= 3.8
* PyTorch == 1.10.1
* Tensorboard
### Dependencies:
1. Install [PyTorch 1.10.1](https://pytorch.org/get-started/previous-versions/) with the correct CUDA version.
2. Set the following environment variable to avoid problems with multiprocess trajectory sampling:
    ```
    export OMP_NUM_THREADS=1
    ```

# Training

You can train your own models using the provided config in `metro/cfg`:

```
python -m metro.train --city_name city_name --cfg demo
```
You can replace `demo` to train other cfgs.

The results are saved in `result/city_name/cfg/seed`




# License
Please see the [license](LICENSE) for further details.
