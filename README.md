# DroneCI Build Status
[![Build Status](https://cloud.drone.io/api/badges/Diaz1401/clang-build/status.svg?ref=refs/heads/main)](https://cloud.drone.io/Diaz1401/clang-build)

# Download
Check latest release [here](https://github.com/Diaz1401/clang/releases/latest)

# Usage
```bash
  mkdir ~/.kucing-clang
  tar xf clang.tar.zst -C ~/.kucing-clang
  echo 'export PATH=$PATH:/home/$USER/.kucing-clang/bin' >> .bashrc
  source ~/.bashrc
  clang --version
```
# Features
```
  ==> Minimal LLVM 14 release branch build targeting 'AArch64' and 'X86'
  ==> Latest Binutils v2.38 release targeting 'aarch64-linux-gnu' and 'x86_64-linux-gnu'
  ==> Stripped binaries
  ==> Minimal download size (only arround 140-150MB)
  ==> Highly compressed tar archive with zstd v1.5.2
  ==> Build Polly & LLD
```
# Build script

  Visit https://github.com/Diaz1401/clang-build
