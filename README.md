**How to run my implementations:**

Every Makefile command will run 100 iterations of 1, 2, 4, 8, 16, and 32 threads. It will output the average number of cycles each threadnum takes in the following format:

Threads: 1, Avg cycles: 4789556.320000

Threads: 2, Avg cycles: 9269000.480000

Threads: 4, Avg cycles: 9669956.320000

Threads: 8, Avg cycles: 13391926.080000

Threads: 16, Avg cycles: 14259841.920000

Threads: 32, Avg cycles: 11489171.840000


**Implementation 1**: Parallel For (in file tri_for.c)

make run_small_for

make run_medium_for

make run_large_for

**Implementation 2**: Parallel Region with reduction (in file tri_par.c)

make run_small_par

make run_medium_par

make run_large_par

**Implementation 3**: Parallel Region with critical regions (in file tri_par_crit.c)

make run_small_crit

make run_medium_crit

make run_large_crit

**Implementation 4**: Parallel Region with atomic regions (in file tri_par_atom.c)

make run_small_atom

make run_medium_atom

make run_large_atom
