# Chrome Rich Presence Client for Discord
Shamelessly show the world what you are browsing on Google Chrome!

## Features
Show statuses of hard coded or generic sites!

![showcase](https://raw.githubusercontent.com/vrevolverrr/chrome-rpc/main/assets/showcase.png)

## Installation
1. Download the latest release and extract the `release` folder
2. Open Google Chrome and go to `chrome://extensions`
3. Check `Developer Mode` at the top right of the page
4. Click `Load Unpacked` and select the `extension` folder in the `release` folder
5. Close all windows of Google Chrome
6. Hold `Windows + X` key and click `Windows PowerShell (Admin)`
7. Type `Set-ExecutionPolicy Bypass` and ENTER, type `A` and ENTER when prompted
7. Click on `Chrome RPC.vbs` to launch Google Chrome with Discord RPC

PS: Create a shortcut of Chrome RPC by `right clicking -> copy` and `right click -> paste shortcut`. To change the icon, `right click -> properties` and `change icon` then `browse` then look for the `chromium.ico` icon in the `release` folder

## Supported Custom Sites
| Website|Custom Activity|Icon
|--------|---------------|----
|Discord|none|✔️
|F2Movies|shows browsing and watching|✔️
|Facebook|none|✔️
|Github|shows repo|✔️
|Gmail|none|✔️
|Google|none|✔️
|Instagram|none|✔️
|Netflix|shows browsing and watching|✔️
|Reddit|shows subreddit|✔️
|StackOverflow|none|✔️
|Twitch|shows watching|✔️
|Whatsapp Web|none|✔️
|Wikipedia|shows article heading|✔️
|YouTube|none|✔️

and more coming soon!

## TODO
- Fix known issues
- Add update notification

## Known Issues
- Some custom activities requires switching tabs to update once the site has loaded
- The launcher is poorly designed therefore is buggy. I am open for solutions!