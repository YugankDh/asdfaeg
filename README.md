# Share a Folder from Windows and Access it on Linux

## Steps to Share a Folder from Windows and Access it on Linux

### 1. Share the Folder from Windows and Allow Discovery
First, make sure you have shared the folder on Windows and enabled network discovery. You can do this by going to your folder properties, selecting the "Sharing" tab, and ensuring network discovery is enabled from the settings.

### 2. Open File Manager on Linux
Open the file manager (such as **Nautilus** or any other you are using) on your Linux machine.

### 3. Navigate to the Network Section
Go to the **Network** section in the file manager to see shared devices on your local network.

![network](https://github.com/user-attachments/assets/7b799fbd-df59-42d7-b486-805cdfe3e6b1)


### 4. Find the Windows Shared Folder
Locate the Windows shared folder on the network. It should appear under the list of shared devices.

![winnet](https://github.com/user-attachments/assets/1b240948-ecc3-429d-8b85-c687b8a83b75)


### 5. Access via IP Address if Necessary
If the shared folder does not appear, try accessing it using the IP address of the Windows machine. Enter it in the file manager using the format: `smb://<Windows-IP-Address>`.

![ip](https://github.com/user-attachments/assets/54e2b715-006f-4547-92b1-84bed701ae64)


Once connected, you should be able to browse and use the shared files from your Linux system.
