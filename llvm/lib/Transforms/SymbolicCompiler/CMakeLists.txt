add_llvm_component_library(LLVMSymbolicCompiler
  Main.cpp
  Pass.cpp
  Runtime.cpp
  Symbolizer.cpp

  DEPENDS
  intrinsics_gen
  )
