# Minecraft Bedrock Edition Dedicated Server Updater for Win & Linux

## Description
This is python based script that can download (&replace) Dedicated Server of Minecraft Bedrock Edition.  
This script has four option of versions and two of downloading.  

### version options:
0. Windows Release
1. Linux Release
2. Windows Preview
3. Linux Preview
### downloading options:
1. Downloading & Replacing : Download & Replace old server
2. Normal Downloading : Just download & UnZip server files  

When choosing replacing mode, this script replace just 3 files.

1. worlds
2. allowlist.json
3. server.properties

If you use behavior packs or resource packs, you have to copy it manually.  

And, you also have to change the name of the server folder which you are using now to `now_server`.  
This operation is needed to let the script detect the folder.  
If you would not like to change the server folder name, please change variable `now_server_path` in `exec_updater.py`.

## Requirement
- Python3
- requests (Python Library)

## How to Use
### 1. Download this scripts
### 2. UnZip and move the files
Move `exec_updater.py` and `update_run.sh` to the directory which has server folder.  
NOT same directory as a file like server.properties
### 3. Change the server folder name
Change the server folder name to `now_server`
### 4. Execute the script
Windows:  
double click or command terminal: `python exec_updater.py`  
Linux:  
`./update_run.sh` or `python3 exec_update.py`

## Author
t-haruki122