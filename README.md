# PhoTorch Studio

Official release downloads for PhoTorch Studio - Advanced photosynthesis model fitting software.

Visit [photorchstudio.app](https://photorchstudio.app) to download. Visit the [PhoTorch repo](https://github.com/GEMINI-Breeding/photorch) or read the [paper](https://arxiv.org/abs/2501.15484) for more info.

## Downloads

### macOS
- [macOS Apple Silicon (M1/M2/M3)](https://github.com/rylekizzo/photorch-studio-releases/releases/latest/download/PhoTorch.Studio_1.0.0_aarch64.dmg) - DMG Installer
- [macOS Intel](https://github.com/rylekizzo/photorch-studio-releases/releases/latest/download/PhoTorch.Studio_1.0.0_x64.dmg) - DMG Installer

### Windows
- [Windows Installer (EXE)](https://github.com/rylekizzo/photorch-studio-releases/releases/latest/download/PhoTorch.Studio_1.0.0_x64-setup.exe) - Recommended
- [Windows Installer (MSI)](https://github.com/rylekizzo/photorch-studio-releases/releases/latest/download/PhoTorch.Studio_1.0.0_x64_en-US.msi) - For enterprise deployment

### Linux
- [AppImage](https://github.com/rylekizzo/photorch-studio-releases/releases/latest/download/PhoTorch.Studio_1.0.0_amd64.AppImage) - Universal, runs on most distributions
- [Debian/Ubuntu (DEB)](https://github.com/rylekizzo/photorch-studio-releases/releases/latest/download/PhoTorch.Studio_1.0.0_amd64.deb)
- [Fedora/RHEL (RPM)](https://github.com/rylekizzo/photorch-studio-releases/releases/latest/download/PhoTorch.Studio-1.0.0-1.x86_64.rpm)

## System Requirements

| Platform | Minimum Version |
|----------|-----------------|
| macOS | 11.0 (Big Sur) or later |
| Windows | Windows 10 or later |
| Linux | Ubuntu 20.04+ or equivalent |

## About PhoTorch Studio

PhoTorch Studio is a desktop application for fitting the Farquhar-von Caemmerer-Berry (FvCB) photosynthesis model to gas exchange data. Built with PyTorch for high-performance scientific computing.

### Key Features

- **FvCB Model Fitting** - Fit A-Ci and A-Q response curves with configurable parameters
- **Temperature Response** - Multiple temperature response functions including peaked Arrhenius
- **Mesophyll Conductance** - Optional gm fitting with CO2 diffusion corrections
- **Interactive Visualization** - 2D and 3D plots with Plotly for data exploration
- **Batch Processing** - Fit multiple curves simultaneously with grouped parameters
- **Data Export** - Download results as XLSX with fitted parameters and model predictions
- **LI-COR Compatible** - Direct import of LI-6800 and LI-6400 data files

## Installation

### macOS
1. Download the DMG for your Mac (Apple Silicon or Intel)
2. Open the DMG and drag PhoTorch Studio to Applications

### Windows
1. Download the EXE installer
2. Run the installer and follow the prompts
3. Launch from the Start Menu

### Linux
For AppImage:
1. Download the AppImage file
2. Make it executable: `chmod +x PhoTorch.Studio_1.0.0_amd64.AppImage`
3. Run: `./PhoTorch.Studio_1.0.0_amd64.AppImage`

For DEB: `sudo dpkg -i PhoTorch.Studio_1.0.0_amd64.deb`

For RPM: `sudo rpm -i PhoTorch.Studio-1.0.0-1.x86_64.rpm`

## Core Engine

The core fitting engine is available as an open-source Python library. See the [PhoTorch repository]([https://github.com/gemini-breeding/photorch](https://github.com/GEMINI-Breeding/photorch) for the source code.


---

2025 PhoTorch Studio. All rights reserved.
