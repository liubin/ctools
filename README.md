
A set of tools to help in understading cassandra database storage internals. More detailed description of storage internals can be found at http://distributeddatastore.blogspot.com

token.py - This script converts a given key to token using RandomPartitioner

sstable.py - This script reads the rows and columns in a given SSTable. User can read columns from a specific row by passing the row key as command line argument. It doesn't require access to cassandra column families in system keyspace to decode SSTable data like sstable2json tool. It is tested with version "jb"

sstable-metadata.py - This script reads the SSTable stats file to display SSTable metadata information. It is tested with version "jb" 
