# Rust In-Memory Blockchain Library

Library to cache blocks or block headers in-memory. 

The cache container allows retrieval as anticipated in Bitcoin applications, determines the chain with most work (the trunk of the tree) and 
verifies if work on a block header is sufficient for the height at which the block tries to connect to the trunk.


