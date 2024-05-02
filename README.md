# Ext2 File System Implementation

A project for UCLA's operating systems course, this repository generates an image of a barebones Ext2 file system. 
Specifially, creates a superblock, a block descriptor table and bitmap, and an inode table and bitmap.
The sample file system generated contains a regular hello world file,
a symbolic link to the hello world file, and a lost and found directory all within the root directory.

This project can be built using its `Makefile`, tested with `test_lab4.py`, and cleaned using
`make clean`.
