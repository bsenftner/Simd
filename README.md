# Simd
my version of https://github.com/ermig1979/Simd, just wrapped in a Visual Studio 2019 Solution. 

The Simd Library is a free open source image processing and machine learning library, designed for C and C++ programmers. It provides many useful high performance algorithms for image processing such as: pixel format conversion, image scaling and filtration, extraction of statistic information from images, motion detection, object detection (HAAR and LBP classifier cascades) and classification, neural network.

The algorithms are optimized with using of different SIMD CPU extensions. In particular the library supports following CPU extensions: SSE2, SSE3, SSSE3, SSE4.1, SSE4.2, AVX, AVX2 and AVX-512 for x86/x64, VMX(Altivec) and VSX(Power7) for PowerPC, NEON for ARM.

The Simd Library has C API and also contains useful C++ classes and functions to facilitate access to C API. The library supports dynamic and static linking, 32-bit and 64-bit Windows and Linux, MSVS, G++ and Clang compilers, MSVS project and CMake build systems.

For more info see https://github.com/ermig1979/Simd
