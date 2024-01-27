# mlx-jax-neural-nets
This repository consits of code written on arm64 based Apple devices.

As of date, MLX only supports metal devices ( due to it's unified memory approach?), while JAX supports functionality on CPU, GPUs (experimental support on Apple Metal) and TPUs.

To install MLX :
```
pip install mlx
```
To install JAX on arm64 Macs:
```
 pip install numpy wheel ml-dtypes==0.2.0
 pip install jax-metal
```


