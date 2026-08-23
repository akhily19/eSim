# eSim Ubuntu 25.04 Compatibility and Installer Improvements

## Overview

This project focuses on improving the compatibility of the eSim EDA Suite installer with Ubuntu 25.04.

The work addresses NGHDL/LLVM compatibility, Python package installation, KiCad 8 configuration, proxy handling, and uninstall confirmation handling.

## Environment

- OS: Ubuntu 25.04
- Virtualization: VirtualBox
- CPU: 1 core
- RAM: ~1.6 GB
- Python: 3.13.3
- KiCad: 8.0.8
- Branch: `installers`

## Key Improvements

### NGHDL and LLVM Compatibility

Updated NGHDL support for Ubuntu 25.04 and configured GHDL to use LLVM 18.

```bash
./configure --with-llvm-config=/usr/bin/llvm-config-18
