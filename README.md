# Collection of easy to use MLIR end to end examples. 
A collection of MLIR End to End examples. We plan to add working examples of:

1. TF2 Saved Model --> MHLO --> C/C++
  *  --> C++ --> target of your choice. With cgoE2E: (https://github.com/iml130/mlir-emitc/tree/cgo) 
  *  --> C++ --> target of your device. With TCIE: (https://gist.github.com/silvasean/8eb20f3649855b64f525c7141033f053)
2. TF2 Saved Model --> MHLO --> LLVM_IR
  * --> RefE2E (?)
  * --> LLVM-IR-e2e in this repo
3. Torchscript --> ATen --> [C++ / LLVM_IR]
  * Use mlir-npcomp to generate ATen Dialect. 
  * Lower to C++ / LLVM_IR (?)
