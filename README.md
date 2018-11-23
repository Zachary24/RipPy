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
| Preset  | Default Value | Description |
| ------------- | ------------- | ------------- |
| instaUser  |   | | Username of your Instagram account  |
| instaPass  |   | | Password of your Instagram account  |
| igslogStatus  | True  | | Capture/Save log of downloaded posts for Instagram  |
| ytdloutputTemplate  | -o 'Rips/Youtube/%(uploader)s/%(title)s - %(id)s - %(upload_date)s.%(ext)s'  | | Default template for storing videos downloaded with youtube-dl  |
| ytdlhandlerTemplate  | --no-check-certificate -f 137/248/136+140  | | Deafult Handlers (Options/ARGS) used when downloading videos with Youtube-dl  |
| ytdlhistoryFile  | history.txt  | | FileName of Youtube-dl history log file, ytdlhistory stores the history files in a list, therefore you can have seperate log files for different categories of content E.G. Documentarys.txt, Trailers.txt, {MUST CONTAIN .TXT}  |
| ytdlhistoryName  | history
| wgetHandlers  |  |
| wikiStatus  | False  |
| configStatus  | False  |
