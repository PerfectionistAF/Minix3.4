============================================================================
			changes
============================================================================
1-create a new file "outerpagetable.h" in the directory: usr/src/servers/vm
2-add 2 variables "vir_bytes inner_pagetable_start" and 
"vir_bytes inner_pagetable_end" at line 107 
in the directory: usr/src/servers/vm/pagetable.c
3-define a new struct at line 59, and change code lines at line 269, and 
line 559 in the directory: usr/src/servers/vm/alloc.c
4-create new file "fifo.c" in the directory: usr/src/servers/pm
5-include "fifo.c" at line 30 in "exec.c" in the directory: usr/src/servers/pm
6-create new file "lru.c" in the directory: usr/src/servers/pm
7-include "lru.c" at line 31 in "exec.c" in the directory: usr/src/servers/pm
8-run make command 
9-run cd ..
10-run make command
11-run cd ..
12-run make build command

