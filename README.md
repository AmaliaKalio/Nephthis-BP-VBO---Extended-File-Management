# Nephthis-BP-VBO---Extended-File-Management
VB object to add functionality missing from the OOB File Management VBO

## Generate Temp File
Generates a temporary file with the specified name. Differs from Generate Unique File in that the file name is not randomly generated.

### Inputs:
* File Name - Text

### Outputs:
* Full Path - Text

## Generate Temp Filder
Generates a temporary folder with the specified name

### Inputs:
* Path - Text

### Outputs:
* Folder

## Generate Unique File Name
Similar to Generate Unique File, but only generates the file name and does not create the actual file

### Inputs:
* Path
* Extension

### Outputs:
* File Name
* Full Path

## Generate Unique File 
Generates a unique file to use

### Inputs:
* Path
* Extension

### Outputs:
* File Name
* Full Path

## Get Downloads Folder
Gets the path to the curfrent default downloads directory

### Outputs:
* Folder

## Move Directory
Moves a directory (ie cut and paste) from one place to another

### Inputs:
* Source Directory - Text
* Destination Directory - Text

### Outputs:
* Success - Flag
* Message - Text

## Unzip
Unzips a directory

### Inputs:
* Source Archive - Text
* Destination Directory - Text

### Outputs:
* Success - Flag
* Message - Text

## Zip
Zips a directory

### Inputs:
* Source Archive - Text
* Destination Directory - Text

### Outputs:
* Success - Flag
* Message - Text
