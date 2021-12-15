# File Organizer
***An app that organizes cluttered folders***

This app makes use of Tkinter

This simple app allows you to organize files by file type.

If you navigate to dist/FileOrg.exe this app should be able to run standalone without any dependency, but if you wish to run the script directly dont forget to do pip install requirements.txt in your terminal

## Sidenotes Before Using
If you choose to use the app as an exe please note that Windows Defender will assume it is a Trojan and will raise an error(Trojan:Win32/Sabsik.FL.A!ml) if you try to move or execute the file (apps packed with pyinstaller seems to have this issue often)
I recommend opening Windows Defender and allowing the "Threat". 

Also, for images to work on other devices, I've converted the banner and icon images into bytes. The script will read the bytes and then write files to your PC. These files are temporary and will be deleted upon closure of the app. You may run into an issue running the exe if your PC has tight read/write permissions. I know this isnt ideal and I'm looking for a workaround that will allow other PC's to render these images in the app without ***visibily*** and ***loosely*** storing the images. 





### Before
![image](https://user-images.githubusercontent.com/74794439/146101001-93bd5de1-27e8-43c2-9180-299c0a66abbf.png)
#### After
![image](https://user-images.githubusercontent.com/74794439/146101311-87c94b9d-5c47-441f-ad90-cdcad6b46ecf.png)
