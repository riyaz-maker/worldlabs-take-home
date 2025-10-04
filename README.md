# World Labs Take Home
Take home exercise for worldlabs focuisng on writing a custom kernel for fp32 and bf16 data types.

## Document that I used for reference
[nvidia-ampere-architecture-whitepaper.pdf](https://github.com/user-attachments/files/22695924/nvidia-ampere-architecture-whitepaper.pdf)

## My thoughts
Implementing warp synchronization and reductions to calculate global sin sum was the most tricky part for me given the transformation logic.

## Results
Results showing bandwidth achieved for (cudaMemcpy(DevicetoDevice)) and the bandwidth achieved for the kernel can be found at the end of the noteboook.

## Note
Physical gpu that i have is gtx 1650 which doesn't support bf16 data types. So, I had to use google colab's A100 and hence the jupyter notebook instead of C++ files and screenshots. I hope that's okay.
