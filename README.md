# Arch Linux Os

**Arch Linux Installation:

Arch Linux is a lightweight and flexible Linux distribution focused on simplicity and user control. Its installation involves manual steps such as partitioning disks, mounting filesystems, installing the base system with pacstrap, configuring the bootloader (like GRUB), setting up networking, and creating a user account. Unlike other distros, Arch provides a minimal base, encouraging users to configure everything themselves for a custom setup.

**System Call Implementation:

In Linux, a system call is a programmed request to the kernel for a service (e.g., file operations, process control). To implement a custom system call in the Linux kernel, we typically:-
>> Write the C function (e.g., in a kernel source file).
>> Add the function prototype to a header file.
>> Assign it a syscall number in the syscall table (e.g., syscall_64.tbl).
>> Recompile and boot into the modified kernel.

This process gives insight into how user-space programs interact with kernel-space functions.







