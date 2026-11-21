# GalaxyAI-A175F
Standalone Galaxy AI + Always On Display (AOD) module for Samsung Galaxy A17 4G (SM-A175F, One UI 9). KernelSU + NoMount required.
# GalaxyAI for SM-A175F

Standalone KernelSU module that enables **Galaxy AI** and **Always On Display (AOD)**
on the Samsung Galaxy A17 4G **(SM-A175F)** running One UI 9 / Android 17.

One ZIP, no base module required.

## Requirements

- Samsung Galaxy A17 4G **SM-A175F**
- Android 17 / One UI 9 (**A175FXXU7DZJ7**)
- MediaTek Helio G99 (MT6789)
- **KernelSU** (samsung branch, late-load)
- **NoMount v2.3.1** metamodule
- root or temporary root

> NoMount is required: the module injects system files through it.
> Use **Soft Reboot** after installation. A cold reboot in temporary-root
> mode removes root, and the module will not be visible until root is obtained again.

## Installation

1. Install KernelSU and NoMount.
2. Download `GalaxyAI-2.6-A175F-standalone.zip` from **Releases**.
3. Install the ZIP as a KernelSU module.
4. Perform a **Soft Reboot**.
5. Verify:
