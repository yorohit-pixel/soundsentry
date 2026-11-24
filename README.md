# SoundSentry

A web app that listens through a laptop or phone microphone and shows visual alerts for six important sounds (smoke/fire alarm, siren, doorbell, knocking, car horn, baby crying). It is a science fair project in the software design category, built for deaf and hard-of-hearing users.

**Try it:** https://yorohit-pixel.github.io/soundsentry/

- Sound recognition uses Google's YAMNet model through MediaPipe, running in the browser.
- Audio is processed live on the device and is never saved or uploaded.
- Works in Chrome (Windows/Mac) and Safari (iPhone). The first load needs internet to download the model.
