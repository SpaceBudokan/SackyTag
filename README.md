# SackyTag
Sackytag is a shell script filesystem based image tagging suite.

Sackytag allows you to use folders and symlinks to create a database of tagged images, using only your file systam and a POSIX compatible shell. It creates a main folder called the "vault," a folder for tags, and a folder for search results. Any images you wish to tag can be moved into the vault or linked into the vault. When images are tagged, a folder with the name of the tag is created in the tags folder (if it does not already exist,) and a symlink to the file (or symlink) in the vault is placed there. To find all images matching a specific set of tags, the folders are searched, and the set of images that have symlinks in every specified folder are returned.
