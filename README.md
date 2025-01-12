# Lua Function with Unexpected Nil Return

This repository demonstrates an uncommon bug in a Lua function involving nil checks. The function `foo` aims to return either `a`, `b`, or their sum, handling nil values for either argument.  However, when both `a` and `b` are nil, it unexpectedly returns nil instead of a default value (e.g., 0).

The `bug.lua` file contains the buggy code, and `bugSolution.lua` provides a corrected version.