# Pre-Installation
* Rename Folder to RipPy
* Place the RipPy folder in your user directory (OPTIONAL)

# Installation
* cd RipPy

**Now you have to install some python3 packages.**
* pip3 install -r Requirements.txt

**Next you need to create some directories.**

* python3 initialSetup.py

# Configure
Change/Update preferences in config.json as needed, please refer to LearnConfig below.

# Start RipPy
* cd RipPy 
* python3 RipPy.py


# LearnConfig
| Function  | Description |
| ------------- | ------------- |
| instaUser  | Username of your Instagram account  |
| instaPass  | Password of your Instagram account  |
| igslogStatus  | {True/False} log downloaded posts for Instagram  |
| ytdloutputTemplate  | Default template for storing videos downloaded with youtube-dl  |
| ytdlhandlerTemplate  | Deafult Handlers (options/ARGS) used when downloading videos with Youtube-dl  |
| ytdlhistoryFile  | Filename of Youtube-dl history log file, the logs are stored in a list, therefore you can have seperate logs for different categories of content E.G. Documentarys.txt, Trailers.txt.  |
| wgetHandlers  | Default handlers (options/ARGS) used when downloading via wget  |
| wikiStatus  | {True/False} Alow download of wiki tables, Default-False,(Semi-Functional)  |
| configStatus  | {True/False} Alow editing of config.json inside of RipPy, Unix only, Default-False  |
