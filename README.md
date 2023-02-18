# OpenDrop For Raspberry pi and a decent home built setup

This is just a small note detailing how to install OpenDrop (https://github.com/jdber1/opendrop) on a Raspberry Pi.

Although Raspberry Pi's have been in short supply for the last couple years (circa early 2021), they still remain popular and the cameras available are still the highest quality to price ratio on the market.

I will be testing out both the processing time per image for both the contact angle and pendant drop, as well as whether the capture works with the current packages available. Some modifications of the base code may be needed, and I may fork the code to make those small modifications.

## The setup
This has been done on a Raspberry Pi 3B with a Raspberry Pi Cam V.2. If it works on the hardware I'll likely purchase a Pi Cam HQ and a decent lens and give that a try too. With some minor modifications to some longer focal length lenses I *should* be able to make a working high resolution optical setup.

## Installing OpenDrop
Installing OpenDrop was a bit of a challenge, but it appears to be possible. I have been doing this over an SSH connection to my mac mini, and passing through the gtk window

