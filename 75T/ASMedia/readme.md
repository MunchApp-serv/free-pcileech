# DMA Firmware Setup Guide

This DMA firmware can be used on both Intel and AMD platforms.

## Installation Steps

1. Flash your DMA card with `pcileech_enigma_x1_top.bin`.
2. Install the driver `ASMediaDriver.EXE` on your main PC.
3. Perform a **cold boot** in both pcs (fully power off the system, then turn it back on).

## Notes

- This firmware works on **both Intel and AMD systems**.
- **Intel platforms** have an advantage: you can keep **IOMMU** and **VT-d** enabled while using this firmware.
- On **AMD systems**, compatibility is expected, but keeping IOMMU enabled has **not been fully confirmed**.

## Disclaimer

This firmware is provided **for free**. It is the same type of firmware that some vendors sell while marketing it as “1:1” or using similar misleading claims.

Use at your own risk.
