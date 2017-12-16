# Mounty: Mount all partitions for forensic analysis
## Features
- Automaticly mount all partitions on an image to your current directory

## Prerequisites
To run Restbot, you will need the following:
- sleuthkit (apt-get install sleuthkit)

# Usage
./mounty [image] 

## Examples
Example mount image.dd to Evidence folder:
```
mkdir Evidence
cd Evidence
mounty ~/image.dd
```
 
## License
Licensed under The MIT License (MIT).
