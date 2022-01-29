add_definitions(${LLVM_DEFINITIONS})
include_directories(${LLVM_INCLUDE_DIRS})

add_llvm_library(SymbolicCompiler MODULE
  Pass.cpp
  Runtime.cpp
  Symbolizer.cpp
  )
