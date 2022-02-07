add_llvm_component_library(LLVMSymbolicCompiler
  Pass.cpp
  Runtime.cpp
  Symbolizer.cpp

  ADDITIONAL_HEADER_DIRS
  ${LLVM_MAIN_INCLUDE_DIR}/llvm/Transforms
  ${LLVM_MAIN_INCLUDE_DIR}/llvm/Transforms/SymbolicCompiler

  DEPENDS
  intrinsics_gen
  )
