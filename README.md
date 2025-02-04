# Lua pairs() Iterator Bug

This repository demonstrates a potential issue with Lua's `pairs()` iterator when dealing with nested tables.  Modifying a table while iterating over it using `pairs()` can lead to elements being skipped, resulting in unexpected behavior.  The `bug.lua` file showcases this issue, while `bugSolution.lua` presents a workaround.