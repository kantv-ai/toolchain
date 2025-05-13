# toolchain

customized toolchain for build Project KanTV and Project ggml-hexagon conveniently.


llvm-mingw-20250305-ggml-ucrt-x86_64.zip: a customized LLVM toolchain to build llama.cpp for target WoA(Windows on ARM) on x86-64 Windows without huge VS2022 IDE(about 19G), size of this file is about 234M. the idea comes from:https://github.com/ggml-org/llama.cpp/pull/12215

HEXAGON_TOOLs_8.8.06.tar.gz: a customized LLVM toolchain to build C/C++ codes running on Qualcomm Hexagon cDSP/NPU. this customized toolchain comes from Qualcomm's Hexagon SDK.
