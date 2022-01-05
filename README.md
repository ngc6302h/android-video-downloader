# android-video-downloader
One-click solution to download videos to your phone

## Prerequisites 
**termux** => https://f-droid.org/en/packages/com.termux/

**termux:API** => https://f-droid.org/en/packages/com.termux.api/



## Requisites
In **termux** run:

```
pkg install python3 ffmpeg &&
python3 -m pip install -U yt-dlp &&
curl -L -o ~/bin/termux-url-opener https://github.com/ngc6302h/android-video-downloader/raw/master/termux-url-opener &&
termux-setup-storage
```
(You can copy this block into the termux console and run it)

After doing this you can exit termux.


## Use
Click the share link button in youtube or other websites or apps top open the app selector, then share **share with termux**. The video will be automatically downloaded.


#### Note:
This repository license only applies to this readme. The commands exposed are free of copyright.
