Usage:

Creating a patch: 

xdelta -e -s old_file new_file delta.file


Applying a patch: 

xdelta -d -s old_file delta.file decoded_new_file
