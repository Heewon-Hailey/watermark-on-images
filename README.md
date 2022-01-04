# Secret messages (watermark) with bandpass filters

## About the project

This work applies bandpass filters to generate an image with a hidden secret message. 

It applies a Gaussian highpass filter to a message image and a Gaussian lowpass filter to a cover image in the Fourier domain. It converts back to the spatial domain to generate the modified image after adding them in the Fourier domain. The key work is to find the proper thresholds of each filter. The secret message should be readable only if you are close enough to the modified image while the image should look like the cover image from a distance.  

---
🖼️ ➕ :speech_balloon: 

Have fun 😉
