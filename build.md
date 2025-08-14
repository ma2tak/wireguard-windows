# Build Instructions

## Windows

1. Install Windows 10 64-bit or Windows Server 2019 and [Git for Windows](https://gitforwindows.org/).
2. Clone the repository:
   ```text
   C:\\> git clone https://git.zx2c4.com/wireguard-windows
   C:\\> cd wireguard-windows
   ```
3. Run the build script:
   ```text
   C:\\wireguard-windows> build
   ```
   The script downloads and verifies required dependencies and produces binaries in `amd64` and `x86` directories.

## Linux

1. Install dependencies:
   ```bash
   sudo apt install mingw-w64 imagemagick
   ```
2. Clone the repository and build:
   ```bash
   git clone https://git.zx2c4.com/wireguard-windows
   cd wireguard-windows
   make
   ```
   The resulting Windows binaries will be placed in the `amd64` and `x86` directories.
