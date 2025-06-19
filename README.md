# Compliance Statement

we should strictly follow Qualcomm's IPR policy, even in open-source community.

# toolchain

customized toolchain for build [Project KanTV](https://github.com/kantv-ai/kantv) and [Project ggml-hexagon](https://github.com/zhouwg/ggml-hexagon) conveniently.


llvm-mingw-20250305-ggml-ucrt-x86_64.zip: a customized LLVM toolchain to build Project ggml-hexagon(a forked llama.cpp focus on a specified backend for Qualcomm NPU) for target WoA(Windows on ARM) on x86-64 Windows without huge VS2022 IDE(about 19G), size of this file is about 234M. this customized toolchain comes from https://github.com/mstorsjo/llvm-mingw/releases, the idea of this customized toolchain comes from:https://github.com/ggml-org/llama.cpp/pull/12215

HEXAGON_TOOLs_8.8.06.tar.gz: a customized LLVM toolchain to build C/C++ codes in Project KanTV and Project ggml-hexagon running on Qualcomm Hexagon cDSP/NPU, size of this file is about 801M. this customized toolchain comes from Qualcomm's Hexagon SDK.


minimal-hexagon-sdk-6.2.0.1.xz: a customized/tailored Hexagon SDK from Qualcomm's official Hexagon SDK 6.2.0.1, size of this file is about 516M. the purpose of this file is to simplify workflow of projects rely on the Hexagon SDK.
