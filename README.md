# Furthest Point Sampling(CUDA Version)

This repository provides `furthest point sampling` algorithm implemented with CUDA. The source codes is originated from https://github.com/erikwijmans/Pointnet2_PyTorch and I reduce its input limit Pytorch Tensor of size \[B, N, 3\] to \[B, N, C\].

## How to Install

```shell
pip install pointnet2_ops_lib/.

# Or if you would like to install them directly (this can also be used in a requirements.txt)

pip install "git+git://github.com/isunLt/fps_cuda.git#egg=pointnet2_ops&subdirectory=pointnet2_ops_lib"
```



