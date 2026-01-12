# KernelSU Kernel Builder for Samsung Galaxy A32 5G (SM-A326B)

## How to Build

1. Fork this repository or create a new repo with these files
2. Go to **Actions** tab
3. Click **Build KernelSU Kernel for Samsung A32 5G**
4. Click **Run workflow**
5. Wait ~30 minutes for build to complete
6. Download the artifact (kernel zip)

## Flashing

After downloading the kernel:

1. Extract `Image` from the zip
2. Use AIK (Android Image Kitchen) to repack boot.img with new kernel
3. Flash via ODIN or fastboot

## Device Info
- Model: SM-A326B
- Kernel: 4.14.x
- KernelSU: v3.0.0
