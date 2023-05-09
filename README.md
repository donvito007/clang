# GitHub Action Build Status
[![CI](https://github.com/Diaz1401/clang-build/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/Diaz1401/clang-build/actions/workflows/build.yml)

# Download
Check latest release [here](https://github.com/Diaz1401/clang/releases/latest)

# Installation
```bash
rm -rf ~/.kucing-clang
mkdir ~/.kucing-clang
tar xf clang.tar.zst -C ~/.kucing-clang
if [ $USER == root ]; then
  echo 'export PATH=$PATH:/root/.kucing-clang/bin' >> /root/.bashrc
  source /root/.bashrc
else
  echo 'export PATH=$PATH:/home/$USER/.kucing-clang/bin' >> ~/.bashrc
  source ~/.bashrc
fi
clang --version
```
# Features
```
  ==> Minimal LLVM 16.0.3 build targeting 'AArch64' and 'X86'
  ==> Latest Binutils v2.40 release targeting 'aarch64-linux-gnu' and 'x86_64-linux-gnu'
  ==> Stripped binaries
  ==> Minimal download size (only arround 160-190MB)
  ==> Highly compressed tar archive with zstd v1.5.5
  ==> Build LLVM Polly & LLD
```
# Build script

  Visit https://github.com/Diaz1401/clang-build
