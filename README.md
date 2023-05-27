# How To Hockey Media Server
Follow the instructions below to access the media server from anywhere with ease (5 mins to setup).

## Download & Install Twingate
[twingate.com/download](http://twingate.com/download "twingate.com/download") (Windows/MacOS, iOS/Android)

## Authenticate with Twingate
1. Click on the Twingate icon in the System Tray (Windows), the Menu Bar (Mac), or open the Twingate app on your phone
2. Click "log in to How To Hockey"
3. Authenticate (sign up/sign in) using the email (or google account) you were invited with (ex. yourname@gmail.com)

## Mount the server to your device (connect)
<img align="left" src="/Windows-Logo.png" alt="" width="50"></img>
### Windows 7/8/10/11

----------
1. Ensure Twingate is running and you are logged in
2. File explorer > Network (Right Click) > Map Network Drive
3. Select available drive letter (eg. M: for media, or P: for Puck Daddy)
4. Server: `\\10.175.1.101\{FOLDER}`
5. Click connect
6. Login using provided credential for media server (username/password) from Haden
7. View drive in File Explorer > This PC
*Repeat steps 2-5 for each folder you want mapped (ex. `\puckdaddy`, `\media` and `\remote`)*

<img src="/macOS-Logo.png" alt="" width="150"></img>
----------
1. Ensure Twingate is running and you are logged in
2. Finder > Go > Connect to Server
3. Server: `smb://10.175.1.101`
4. Click connect
5. Login using provided credential for media server (name/password) from Haden
6. Access in Finder

[<img align="left" src="/documents-app-icon.png" alt="" width="50"></img>](https://apps.apple.com/ca/app/documents-file-manager-reader/id364901807)
### iOS Documents - File Manager (Recommended)
*This app seems to work better than the native iOS Files app especially for larger files*

-------
1. Ensure you are logged in on the Twingate app
2. Disconnect from any VPN (ex. NordVPN, ExpressVPN)
3. Install and open "[Documents - File Manager](https://apps.apple.com/ca/app/documents-file-manager-reader/id364901807)"
4. My Files > Plus sign (+) > Add Connection > Windows SMB
5. Title: `Something obvious to you` (eg. Puck Daddy Server)
6. URL: `smb://10.175.1.101` Domain: `Leave blank`
7. Login using provided media server credential from Haden (Login: `username` Password: `password`)
8. Done
9. Access from "My Files" in home screen of the Documents app

### IOS Files App

----------
1. Ensure you are logged in on the Twingate app
2. Disconnect from any VPN (ex. NordVPN, ExpressVPN)
3. Open Files app
4. Go back until root "Browse" screen
5. Tap elipse menu in top right (3 dots)
6. Connect to server: smb://10.175.1.101
7. Login as "registered user" using credential provided by Haden
8. Click next
9. Access via 10.175.1.101 in "Browse" screen

**If you have any questions or issues contact [Haden](mailto:haden@howtohockey.com)**
