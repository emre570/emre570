hi, i'm emre — ml systems & performance engineer.

i build and optimize inference systems for production: low-latency 
audio models, custom CUDA/CuTe-DSL kernels, and the surrounding 
infrastructure that makes them ship.

**recent work:**
- shipped 430ms → 50ms STT latency in production (8.6x) via FP8 
  quantization, fused kernels, and CUTLASS EVT epilogues, [see the blog](https://emre570.bearblog.dev/stt-blog-8x/) 
- contributed Consumer Blackwell (SM120/SM121) support to 
  [Dao-AILab/quack](https://github.com/Dao-AILab/quack) — RMSNorm, 
  softmax, cross-entropy kernels in CuTe-DSL (merged)
- merged PR on [NVIDIA/CUTLASS](https://github.com/NVIDIA/cutlass): 
  Snake activation as a SM90 EVT op

focus: GPU kernel engineering, inference latency, and production 
deep learning systems.

[linktr.ee/emre570](https://linktr.ee/emre570)
