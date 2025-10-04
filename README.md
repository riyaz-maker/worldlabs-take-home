# World Labs Take Home
Take home exercise for worldlabs focuisng on writing a custom kernel for fp32 and bf16 data types.

## Document that I used for reference
[nvidia-ampere-architecture-whitepaper.pdf](https://github.com/user-attachments/files/22695924/nvidia-ampere-architecture-whitepaper.pdf)

## My thoughts
Implementing warp synchronization and reductions to calculate global sin sum was the most tricky part for me given the transformation logic.
