# SoundCloud UWP App (Ad-free)
## Disclaimer
This is the official SoundCloud Xbox app, downloaded as an AppxBundle. It runs perfectly on Windows. It's even called "SoundCloud for Xbox and Windows 10" when loging in, even though it never got released for Windows officially.

**No code is edited, this file was directly pulled from the MS Store (It is signed by Microsoft too). It is ad-free because of a bug and can be fixed at anytime by SoundCloud (if this bug is server-side, otherwise it will stay forever <3).**

I uploaded this here to make it more available for download, since you can't find the original SoundCloud AppxBundle file online.

[SoundCloud Xbox/UWP App Website](https://soundcloud.com/xbox-app)

[Video of the archived App](https://www.youtube.com/watch?v=W1Exge-l5jo&t=21s)

**All Credits go to the original SoundCloud Xbox App developers! This GitHub repository only acts as an archive.**

## Installation
1. Download the latest file [here](https://github.com/devilAPI/soundcloud-adfree-uwp-app/releases/latest)
2. Open the file
3. Press "Install"

If the Installation fails, try installing the Appx via Powershell. Make sure the Path is correct.

Command:
```powershell
Add-AppxPackage -Path "SoundcloudLtd.SoundCloud-MusicAudio_1.1.36.0_neutral___2xc63xn306dnw.AppxBundle"
```



## Compatibility
Tested on Xbox and Windows 11.

Should work with all UWP-compatible devices: *PC, Xbox, Surface Hub, HoloLens and Windows Phone*. 

## Known Bugs
Currently there were no app-breaking bugs found. Please note that bugs won't be fixed because the app is made by SoundCloud themselves.

**Windows:**
- Volume Slider **sometimes** disappears on playing now screen (usually not a problem)
- Theres no blurred cover background
- Text can be highlighted (This can also be a Feature not a Bug)
