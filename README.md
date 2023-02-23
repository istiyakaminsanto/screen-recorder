# Screen Recorder For KAS (Kings Apps Studio)

## Features
🎥 Make unlimited recordings of your tab, desktop, any application, and camera<br>
✏️ Annotate by drawing anywhere on the screen, adding text, and creating arrows<br>
👀 Highlight your clicks, focus on your mouse, or hide it from the recording<br>
🎙️ Individual microphone and computer audio controls, push to talk, and more<br>
⚙️ Custom countdowns, show controls only on hover, and many other customization options<br>
💾 Export as mp4, gif, and webm, or save the video directly to Google Drive<br>
✂️ Trim or remove sections of your recording<br>
🌐 Available in English, Catalan, Spanish (by [Carmen Madrazo](https://twitter.com/Carmen_M_A)), French (by [Marie](https://twitter.com/marie_dm_)), Portuguese, Brazilian Portuguese, German (by [Christian Heilmann](https://github.com/codepo8)), Korean (by [
Dong-Hyeon, Kim](https://github.com/blood72)), Chinese (by [xkonglong](https://github.com/xkonglong)), Polish (by [Damian Harateh](https://github.com/harad1)), Russian (by [Artem](https://github.com/blinovartem)), Tamil (by [MC Naveen](https://github.com/mcnaveen)), Turkish (by [Can Mavioğlu](https://github.com/canmavi)), Italian (by [Angelo](https://github.com/AngeloBottazzo)), Hindi (by [
Pranjal Aggarwal](https://github.com/pranjalagg)), and Indonesian (by [Galang Aprilian](https://github.com/GlgApr))<br>
...and much more - all for free & no sign in needed!<br>

[Here's a Google Sheet](https://docs.google.com/spreadsheets/d/1juc1zWC2QBxYqlhpDZZUNHl3P6Tens6YiChchFcEJVw/edit?usp=sharing) to compare Screen Recorder features with other free & premium screen recorders available for Chrome.

## Libraries used

- [jQuery](https://jquery.com/) -  for better event handling and DOM manipulation
- [FabricJs](http://fabricjs.com/) -  for interactive text and arrows (optimized custom build)
- [FFMPEG](https://www.ffmpeg.org/) - to convert the video to GIF or MP4
- [Jquery Nice Select](https://hernansartorio.com/jquery-nice-select/) - for better, more stylish dropdowns
- [Nouislider](https://github.com/leongersen/noUiSlider) -  for the range sliders used for trimming / removing parts of the recording
- [Pickr](https://github.com/Simonwep/pickr) - for the color picker
- [Plyr](https://github.com/sampotts/plyr) - for the video player shown when editing the recording
- [StreamSaver.js](https://github.com/jimmywarting/StreamSaver.js) - for saving the video asynchronously while recording
- [fix-webm-duration](https://github.com/yusitnikov/fix-webm-duration) - for making the downloaded videos seekable
