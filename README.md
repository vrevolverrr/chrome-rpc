# Chrome Rich Presence Client for Discord
Shamelessly show the world what you are browsing on Google Chrome on Discord with Chrome Rich Presence Client!

## Features
Show your Google Chrome activity on Discord!

![showcase](https://raw.githubusercontent.com/vrevolverrr/chrome-rpc/main/assets/showcase.png)

## Installation
1. Download the [latest release](https://github.com/vrevolverrr/chrome-rpc/releases/download/0.2/release.zip) and extract the `release` folder
2. Open Google Chrome and go to `chrome://extensions`
3. Check `Developer Mode` at the top right of the page
4. Click `Load Unpacked` and select the `extension` folder in the `release` folder
5. Edit `config.json` in the `release` folder to change with notepad or any other editor to change configuration settings

## Ussage
1. Run `launcher.exe` in the releases folder to start Google Chrome with Discord Rich Presence
2. (Optional) Create a shortcut of `launcher.exe` and rename it to whatever you like eg: Chrome RPC and change the icon of the shortcut by going to properties

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
|Messenger|none|✔️
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
- Subreddit of some reddit threads are not detected