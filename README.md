# Stateless Meta JSON Viewer
## Original and SadBIOS's Repository given below. ↓
*And additional information is added by Me at the very end.*

This project is proudly inspired by **Sam's** repository:
- [main.py](https://github.com/Samkaka22/Old-Messenger-Chats-Format-Converter/blob/main/main.py) from [Old-Messenger-Chats-Format-Converter](https://github.com/Samkaka22/Old-Messenger-Chats-Format-Converter/)

While Sam's project converts newer Meta JSON chat exports back into the classic HTML format, **Stateless-Meta-JSON-Viewer** provides a modern, interactive, client-side single-page viewer with instant searching, media support and dynamic customization. All this without the need for any cloud based resources to this can be used completely offline.


## How to Export Your Data from Facebook & Messenger

Before using the viewer, you will need to download your chat data from Meta:
- [Export a copy of your Facebook information](https://www.facebook.com/help/212802592074644)
- [Download your data from Messenger end-to-end encrypted chats](https://www.facebook.com/help/messenger-app/677912386869109)



## Project File Structure

Download the [package](https://github.com/SadBIOS/Stateless-Meta-JSON-Viewer/releases/download/v0.4-pre/json_conv_v-004.zip) from [Releases](https://github.com/SadBIOS/Stateless-Meta-JSON-Viewer/releases/tag/v0.4-pre) section and `unzip` the archive. It should result in the following file structure.

```text
root/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── app.js
└── assets/
    ├── icon.png
    ├── IBM_Plex_Sans/
    │   ├── IBMPlexSans-VariableFont_wdth,wght.ttf
    │   └── static/
    │       ├── IBMPlexSans-Regular.ttf
    │       ├── IBMPlexSans-Medium.ttf
    │       ├── IBMPlexSans-SemiBold.ttf
    │       └── IBMPlexSans-Bold.ttf
    ├── IBM_Plex_Sans_JP/
    │   ├── IBMPlexSansJP-Regular.ttf
    │   ├── IBMPlexSansJP-Medium.ttf
    │   ├── IBMPlexSansJP-SemiBold.ttf
    │   └── IBMPlexSansJP-Bold.ttf
    └── IBM_Plex_Sans_Arabic/
        ├── IBMPlexSansArabic-Regular.ttf
        ├── IBMPlexSansArabic-Medium.ttf
        ├── IBMPlexSansArabic-SemiBold.ttf
        └── IBMPlexSansArabic-Bold.ttf

```

> [!WARNING]
> I am not a designer so forgive the garish blue color palette. I'll hopefully get back it **Soon™**

# I Clean and Redesign almost everything...
## How to use it
 1. Download full Project.
 2. Unzip it (pure optional this project fully offline local browser based so it can even run from a zip file)
 3. Double click *index.html* it will open UI
 4. Upload Meta's json file.
      for example : Select a _Meta JSON file to load_ and *Browse* for upload (conversation-pull.json)
 5. For image and other media, Load MEDIA folder

# This whole project is self-explanatory. so that means it's easy to understand on its own without needing extra details. Enjoy
