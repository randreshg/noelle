noelle_tool_declare(LoopStats)
target_sources(
  LoopStats
  PRIVATE
  src/LoopStats.cpp
  src/LoopStats_Dependences.cpp
  src/LoopStats_InductionVariables.cpp
  src/LoopStats_Invariants.cpp
  src/LoopStats_Loops.cpp
  src/LoopStats_Printer.cpp
  src/Pass.cpp
)

