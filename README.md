# FileManagementCollective
Tools to effectively manage files

[**R3**](https://github.com/978-9-17-637879-3/R3)

Recursive* Regex Renamer.

Rename files in current and sub-directories with full ECMAscript regex. Useful for mass stripping of data or making file names conform to a certain standard.

*The process was switched to an iterative approach early on in order to prevent stack overflow as well as allow easy switching between BFS and DFS.

[**RedoRename (WIP)**](https://github.com/978-9-17-637879-3/RedoRename)

Sync file renames between copies of a directory.

Imagine you create a clone of a directory of records, and then move around some files in the source. You can sync those changes by deleting paths that don't match on the destination and adding the new ones, but that's wasteful. Instead, RedoRename allows you to scan file contents themselves and perform the same rename actions on the destination.