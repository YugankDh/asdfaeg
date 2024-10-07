# Share a Folder from Linux to Windows

## Steps to Share a Folder from Linux to Windows

### 1. Install Samba and Required Packages
Samba allows file sharing between Linux and Windows. To install it, run the following commands in the terminal:
```bash
sudo apt update
sudo apt install samba
sudo apt install nautilus
sudo apt install nautilus-share
```

### 2. Open Nautilus File Manager
Use the **Files** (Nautilus) file manager to access your folders. You can search for it by pressing the Super key (Windows key on some keyboards) and typing `nautilus` as shown in the image.

![find](https://github.com/user-attachments/assets/4cc1d453-9229-42b1-a2e7-7e81eec72a8a)


### 3. Right-click on the Folder to Share
Navigate to the folder you wish to share with Windows, right-click on it, and select **Local Network Share**.

![option](https://github.com/user-attachments/assets/080ad6e6-41de-427d-8c57-0a6854d84f59)


### 4. Enable Sharing
Once you click "Local Network Share", a sharing options window will appear. Enable the options like "Share this folder" and, if necessary, "Allow others to create and delete files in this folder". If you want the folder to be accessible without a password, enable guest access.

### 5. Access the Shared Folder from Windows
On your Windows machine, press `Win + R` to open the Run dialog and type `\\<Linux IP Address>` (replace `<Linux IP Address>` with the IP of your Linux machine). You should now be able to see the shared folder.
