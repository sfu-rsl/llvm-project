add_llvm_component_library(LLVMSymbolicCompiler
  Pass.cpp
  Runtime.cpp
  Symbolizer.cpp

  DEPENDS
  intrinsics_gen
  )
