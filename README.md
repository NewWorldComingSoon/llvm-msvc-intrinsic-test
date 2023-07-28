# llvm-msvc-intrinsic-test

Intrinsic test for llvm-msvc.

## Requirements

- Visual Studio 2022
- CMake 3.15+
- [WDK 11](https://learn.microsoft.com/en-us/windows-hardware/drivers/download-the-wdk)
- [llvm-msvc](https://github.com/NewWorldComingSoon/llvm-msvc-build/releases)

## Building with llvm-msvc

```
cmake -Bbuild -TLLVM-MSVC_v143 -DCMAKE_WIN64_DRIVER=1
cmake --build build --config Release
```
