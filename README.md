# MultiOgar-Edited

A fast, open source server that supports multiple protocol versions and smooth vanilla physics.

Since August of 2016, [Barbosik](https://github.com/Barbosik) has stopped working on this project. Than I get that MultiOgar-Edited version from one of Latvian company. So now I'm working with current version and in future will rename that project 

## Information
Current version : **1.6.1**

## Installation
### Windows:
* Download and install node.js: https://nodejs.org/en/download/ 
* Download this repo
* Unzip MultiOgar-Edited code into some folder.

1. Run the win-Install_Dep.bat file.
2. Run win-Start.bat
* All these files can be found in the *run* folder.

*Manual*
Installing required modules.
```batch
:: Install Required Modules.
npm install

:: Starting the server. 
cd src
node index.js
```

#### Linux:
```bash
# First update your packages:
sudo apt-get update

# Install git:
sudo apt-get install git

# Install node.js:
sudo apt-get install nodejs-legacy npm

# Clone MultiOgar-Edited:
git clone git://github.com/Megabyte918/MultiOgar-Edited.git

# Install dependencies:
cd MultiOgar-Edited
npm install

# Run the server:
cd src
sudo node index.js
```

## Gallery
### Console:
![Console](http://i.imgur.com/bS5ToRD.png)

### Gameplay:
![Gameplay](http://i.imgur.com/XsXjT0o.png)

### Performance:
Version 1.2.8 (Original MultiOgar): 
* 1000 bots, 500 viruses, 1000 foods, map 14142x14142
* Works slightly slower than normal, speed decreases gradually as bots get larger.
* CPU load: 14% (x4 cores)
* Memory usage: 70 MB
* MS response time: Minimum of around 78

Version 1.6.0 (MultiOgar-Edited):
* 1000 bots, 500 viruses, 1000 foods, map 14142x14142
* Works very-very smooth, speed decreases gradually as bots get larger.
* CPU load: 24% (x2 cores)
* Memory usage: 35 MB
* MS response time: Minimum of around 45
