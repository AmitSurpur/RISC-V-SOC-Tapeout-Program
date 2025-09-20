# OpenLane Toolchain Setup (Native Install)

This repository provides installation instructions and setup scripts for a digital design toolchain including:

- **OpenLane** (native, no Docker)
- **Yosys** (from YosysHQ)
- **Icarus Verilog (iverilog)**
- **GTKWave**

---

## System Requirements

- **Operating System:** Ubuntu 22.04 LTS or higher (64-bit)
- **RAM:** ≥16 GB recommended
- **Disk Space:** ≥50 GB (OpenLane builds + temp files)
- **CPU:** 4 cores or more
- **Git:** Latest version
- **Python:** ≥3.10

---

## Installation Steps (Native)

### 1. Update system and install dependencies
```bash
sudo apt update && sudo apt upgrade -y
sudo apt install -y build-essential git curl wget unzip python3 python3-pip bzip2 pkg-config cmake \
libreadline-dev libffi-dev tcl-dev libboost-all-dev libeigen3-dev iverilog gtkwave

