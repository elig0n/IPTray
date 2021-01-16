# ![IPTray Icon](ip.ico?raw=true) IPTray
System tray app that lets you easily find your internal and external IP and hostname.

## Features
- Hover balloon that shows external IP, external hostname and internal IP.
- Right-click menu actions to copy each.
- Left clicking on the tray icon refreshes information. 

## Implementation
- Written for Windows OS using win32api with Python.
- Uses [ipify](http://www.ipify.org) API for retrieving the external IP and `socket.gethostname()` for the internal IP.
