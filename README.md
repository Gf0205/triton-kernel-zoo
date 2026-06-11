# Triton Kernel Zoo ??

High-performance GPU kernels in Triton with comprehensive benchmarks.

## Benchmarks (RTX 3090 / T4)

| Kernel | vs PyTorch | vs cuBLAS | Status |
|--------|-----------|-----------|--------|
| vector_add | ~1.0x | N/A | ? |
| softmax | WIP | N/A | ?? |
| rmsnorm | TODO | N/A | ? |
| gemm | TODO | TODO | ? |
| flash_attn_prefill | TODO | TODO | ? |
| paged_decode_attn | TODO | TODO | ? |

## Environment
- GPU: NVIDIA RTX 3090 (24GB)
- CUDA: 12.x
- Triton: latest
