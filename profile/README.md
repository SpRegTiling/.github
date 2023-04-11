# Sparse Register Tiling

Sparse Register Tiling is a new technique composed  of an unroll-and-sparse-jam transformation followed by data compression that is specifically tailored to sparsity patterns in unstructured sparse neural networks. Unroll-and-sparse-jam uses sparsity information to jam the code while improving register reuse. Sparse register tiling is evaluated across 2396 weight matrices from transformer and convolutional models with a sparsity range of 60-95\% and provides an average speedup of 1.72x and 2.65x over MKL SpMM and dense matrix multiplication, respectively, on a multicore CPU processor.


# Getting stasted
Sparse register tiling code base is publicly available from [sparse-register-tiling](https://github.com/SpRegTiling/sparse-register-tiling).



