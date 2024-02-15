# ID1110-W06
Introduction to Programming Course Project, Semester 2
Please retain the directory structure for smooth functioning of code.

Note: Only windows systems will support automatic installation of necessary modules.
Please refer to requirements.txt for requirements for different OS.

SUMMARY: 
The project can be easily run on any windows machine (with admin access as some modules require installation which could be restricted on networked computers). The script automatically starts installation of necessary modules on running it the first time (only for windows). The sign language detection script is run. It detects the sign based on the inputs already stored in the trained_model.p file if it exists.

Note : The ASL script needs to be trained if the model doesn’t exist. The github repository has an uploaded model with letters A,B,C stored and trained, thus it is recommended to use that. If you want to make your own trained symbol file, make necessary changes to the file by modifying and running the other python files in order data_collection, data_creation and data_trainer respectively.
