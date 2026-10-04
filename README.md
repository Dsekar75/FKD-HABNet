# FKD-HABNet
FKD‑HABNet: Federated Knowledge Distillation‑enhanced Hybrid Adaptive Binarized Neural Networks. Combines ALAB, PGB, RASD, dual BN, and quantization to improve stability, representation, and robustness under non‑IID data, achieving high accuracy with reduced communication and memory.
# FKD-HABNet

Federated Knowledge Distillation-enhanced Hybrid Adaptive Binarized Neural Networks (FKD-HABNet) combine ALAB, PGB, RASD, AT+BN, and quantization to improve stability, representation, and robustness under non-IID data. Achieves 92.1% accuracy on CIFAR-10 with 75% communication reduction.

## Key Ingredients
- **ALAB**: Adaptive Long-Tailed Activation Binarization for gradient stability
- **PGB**: Pre-activation Guided Binarization for feature preservation
- **RASD**: Reduced Approximate Stochastic Depth for generalization
- **AT+BN**: Adversarial Dual Batch Normalization for robustness
- **Quantization**: 8-bit compression for communication efficiency
- **FKD**: Federated Knowledge Distillation for global teacher aggregation
