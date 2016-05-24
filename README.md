# CS525 Project

## Implementation of a database system

This implementation has the following features:
* Storage manager that allows read/writing of blocks to/from a file on disk
* Buffer manager that manages a buffer of blocks in memory including reading/flushing to disk and block replacement (flushing blocks to disk to make space for reading new blocks from disk)
* Record manager that allows navigation through records, and inserting and deleting records
* Disk-based B+-tree index structure