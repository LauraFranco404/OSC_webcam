# **SOI Workshop 2**
## Laura Franco
---
Pan control using computer vision

This project integrates Python and Pure Data to control stereo sound panning based on visual information captured by the camera.

The Python program processes the video frames, calculates the average brightness per column, and determines which side of the image has the highest luminance.
Based on this value, a signal is sent to Pure Data, where the audio panning is dynamically adjusted toward the channel (left or right) corresponding to the brightest side of the frame.

[Workshop Video](https://javerianacaliedu-my.sharepoint.com/:v:/g/personal/lcfranco_javerianacali_edu_co/EbBCCIPX4Q9DsL180NPh6jkBE9GZyCiT4pjqrIf9V6KtWA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=uc6v99)
