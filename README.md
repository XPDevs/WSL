# WSL
this is the WSL (windows subsystem for linux) files without installing 
[Download the files](https://www.mediafire.com/file/31ybxcr37gjgyce/WSL.zip/file)


after diwnloading the zip file and extract it and then on the desktop or any toher folder create a foler labled WSL-F and place the extracted WSL folder in that it hsould be 
WSL-F
|----WSL
|     |----wsl.exe
|     |----(the other WSL files and fodlers added)
| 
|-----WSL.bat

on the WSL-F folders root add a batch file called WSL.bat this will start the WSL.exe file 

@echo off

:WSL
echo starting WSL please wait..
"WSL/wsl.exe"

WSL.bat contents:


