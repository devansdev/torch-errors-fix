# torch-errors-fix

1. https://github.com/torch/torch7/issues/1086

export TORCH_NVCC_FLAGS="-D__CUDA_NO_HALF_OPERATORS__"
./install.sh
