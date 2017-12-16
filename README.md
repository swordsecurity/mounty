# Mounty: Mount all partitions for forensic analysis
## Features
- Automaticly mount all partitions on an image to your current directory

## Prerequisites
To run mounty, you will need the following:
- sleuthkit (apt-get install sleuthkit)

## Installation
### Git clone this repository
```
git clone https://github.com/swordsecurity/mounty/
```

### Add mounty to PATH
Add mounty to PATH if you wish to execute mounty directly with the mounty command.
```
echo 'export PATH=$PATH:[path_to_mounty]' >>  ~/.bashrc
```

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
