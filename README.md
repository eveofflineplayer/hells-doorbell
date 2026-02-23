# EVE Online Chain Kill Alert Browser Extension

A lightweight **browser extension** for EVE Online players using **Pathfinder** (wormhole mapping tool) that provides **real-time notifications** for kills happening in your chain.

This tool helps you quickly spot activity, respond to threats, find content, or third-party fights — all without constantly staring at zKill or other external sites.

I've personally found quite a bit of good content using this already. If you're hunting fights in your wormhole chain, this should be a handy addition to your setup!

## ✨ Current Features

- **Sound alert** when a kill occurs in your chain
- **Visual highlight** on the Pathfinder system map where the kill happened  
  (lasts 60 seconds or until you click the system)
- **Snackbar** with quick kill information (to be redesigned/improved in future)
- **History window** showing missed kills with relevant details
- **System tag** displayed (e.g. C4F)
- Direct link to the **killmail on zKillboard**
- Direct link to the **final blow pilot** on EVE Apex
- **Hover** over a history entry → temporarily re-activates the visual effect on that system (great for navigation)
- Option to **dock the extension** to the **left** or **right** side of the screen

## 🚀 Installation (Very Simple)

1. Extract the downloaded `.zip` file to a folder of your choice
2. Open your browser's extensions page:
   - **Brave**: `brave://extensions/`
   - **Chrome**: `chrome://extensions/`
   - (works on other Chromium-based browsers too)
3. Enable **Developer mode** (toggle usually top-right)
4. Click **Load unpacked** (top-left area)
5. Select the folder you extracted → OK / Select Folder
6. Refresh your **Pathfinder** page

Watch the quick install & demo video:  
https://www.youtube.com/watch?v=Yld5BeE3rFo

## 🎯 Purpose & Benefits

This extension lets you **react fast** to activity inside your wormhole chain.  
Whether you're defending, hunting content, looking for third-parties, or just want to know what's happening in real time — it gives you an edge without needing to tab out constantly.

Happy hunting o7


## Usage outside of Nova Prospect Enterprises & Dark Venture Corporation

Edit ./manifest.json and replace all instances of "https://pf.darkventure.space/" with your own pathfinder link.

As the extension heavily relies on SOCKET.KILL you will need to get your pathfinder link whitelisted. Reach out to SOCKET.KILL with the link below.

## Powered by
The extension is powered by the live kill feed websocket at https://socketkill.com