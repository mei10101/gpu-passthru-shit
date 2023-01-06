# GPU-PASSTHRU scripts
- Scripts and configs for gpu passthrough through QEMU/KVM for my dumbass
- only works on arch based distros
- [based on manjaro gpu-passthru helper](https://github.com/pavolelsig/manjaro_helper_2021)

# Preparations
Make sure u have these enabled
- IOMMU, SVM Mode (AMD) 
- VT-d, VT-x (Intel) 
And then clone the repository by typing:
```
git clone https://github.com/mei10101/gpu-passthru-shit && cd gpu-passthru-shit
```
