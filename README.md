# Deselect mesh objects that have different geometry than the active object
This script deselects objects that have different geometry than the active object, The purpose of this script is to deal with large amounts of duplicate objects.

The way it works, is calculating the average normals of active object faces and faces count, then comparing the other selected objects average faces normals and faces count to the active object, every object that have different faces normal average or differenct faces count will be deselected.

To use this script, select mesh objects, when running the script, all objects that have different geometry will be deselected
