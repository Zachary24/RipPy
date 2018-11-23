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
| instaUser  |   | 
| instaPass  |   |
| igslogStatus  | True  |
| ytdloutputTemplate  | -o 'Rips/Youtube/%(uploader)s/%(title)s - %(id)s - %(upload_date)s.%(ext)s'  |
| ytdlhandlerTemplate  | Content Cell  |
| ytdlhistoryFile  | Content Cell  |
| wgetHandlers  | Content Cell  |
| wikiStatus  | Content Cell  |
| configStatus  | Content Cell  |
