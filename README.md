# Pre-Installation
* Git Clone OR Download RipPy.
* Rename Folder to RipPy if needed.
* Place the RipPy folder in your user directory (OPTIONAL)

# Installation
* cd RipPy

**Now you have to install some python3 packages.**
* pip3 install -r Requirements.txt

**Next you need to create some directories.**

* python3 initialSetup.py

**Now you can run RipPy, please see Configure below first**

* python3 RipPy.py

# Configure
**Change/Update preferences in config.json as needed.**

| Function  | Description |
| ------------- | ------------- |
| instaUser  | Username of your Instagram account  |
| instaPass  | Password of your Instagram account  |
| igslogStatus  | {True/False} log downloaded posts for Instagram  |
| ytdloutputTemplateV  | Default template for storing regular videos/channels using youtube-dl  |
| ytdloutputTemplatePL  | Default template for storing playlists using youtube-dl  |
| ytdlhandlerTemplate  | Deafult Handlers (options/ARGS) used when downloading videos with Youtube-dl  |
| ytdlhistory  | Filename of Youtube-dl history log file, the logs are stored in a list, therefore you can have seperate logs for different categories of content E.G. Documentarys.txt, Trailers.txt.  |
| ytdlEmail  | Email for login (Youtube)  |
| ytdlPass  | Password for login (Youtube)  |
| wgetHandlers  | Default handlers (options/ARGS) used when downloading via wget  |
| wikiStatus  | {True/False} Alow download of wiki tables, Default-False,(Semi-Functional)  |
| configStatus  | {True/False} Alow editing of config.json inside of RipPy, Unix only, Default-False  |
