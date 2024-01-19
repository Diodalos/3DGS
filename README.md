# 3DGS
SLAM using 3D Gaussian splatting

## Installation pacakges
* Using Git Bash
* See VSCode-tutorial https://demun.github.io/vscode-tutorial/git/
### Install vcpkg
```bash
git clone https://github.com/microsoft/vcpkg
cd vcpkg
./bootstrap-vcpkg.bat
```

### Install COLMAP
```bash
./vcpkg install colmap[cuda,tests]:x64-windows
```

## Implement with Colab
https://gist.github.com/kwea123/f0e8f38ff2aa94495dbfe7ae9219f75c