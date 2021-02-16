# Bike-Car-Presence-Detection
Based from https://github.com/aderusha/MQTTCarPresence

I use this for our motorbikes (the cars have to live in the street)

I've added in my automation as I've not wanted it to open the garagedoor unless I've been running the bike for at least 10 minutes. Often we push the bikes out into the drive and then start them. I don't want the door to open as we drive away.

Dr ZZZs does a video with open and closing garage door. As we only exit from the main garage door and can control it from the phone, we avoid having timing issues with the door closing. I am thinking of using a motion sensor to detect if someone is in the garage before closing, but not got there yet.

This is based on Dr ZZs's video: https://www.youtube.com/watch?v=1DyblwsjfU8&t=296s

On a side note, I used a basic ESP12 chip on an adaptor board (with a ht7333 voltage regulator - that can take up to 15V, so should work on the bike). I was tearing my hair out with it constantly rebooting. Added a 100uF capacitor across the GND and ESP VCC and it all works perfectly. I am planning to replace this with a Tantalum capacitor - as the Electrolytic capacitor is too big.

Here are some photos of the board and the cover I created:
<img src="ESP Front.png" alt="ESP Front">
