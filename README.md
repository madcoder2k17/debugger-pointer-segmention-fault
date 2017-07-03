# debugger-pointer-segmention-fault
For new programmers, debugging errors associated with pointers can be a nightmare. "Segmentation Fault (core dumped)" is a pretty vague error message, and it's even worse when strange bugs start appearing that don't cause segmentation faults -- but that result in things like memory getting overwritten in unexpected ways.   But finding problems with pointers is easier than you'd think. Those segfaults often turn out to be among the easiest bugs to find, and using special tools such as Valgrind, even finding buffer overflows is simplified.        This tutorial assumes that you have a basic knowledge of pointers such as can be acquired by reading a pointer tutorial. It would help to be running a system that has a debugger such as GDB, or to at least have sufficient familiarity with GDB-like debuggers to understand the examples presented. Finally, for finding buffer overflows and other invalid uses of memory, you will fare best with Valgrind, though none of the examples will use it.
