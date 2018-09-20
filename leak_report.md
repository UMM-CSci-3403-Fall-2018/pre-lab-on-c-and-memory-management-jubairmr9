# Leak report

# 46 bytes of data lost in 6 blocks. It is because of the lost pointer that could no longer be freed.
# Used free() and 'result' as the variable. That fixed the memory leak.

_Use this document to describe whatever memory leaks you find in `clean_whitespace.c` and how you might fix them. You should also probably remove this explanatory text._

