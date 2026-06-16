# ElectricTekken

As seen on TV here: https://www.youtube.com/watch?v=mvOIEO3RsKk
Brought to by Mirage Esports and PiShock

### *DON'T PUT SHOCKERS ON ANY VITAL AREAS. SEE PISHOCK USERS GUIDE FOR DETAILS. DON'T BE AN IDIOT.*

This is just a funny little python program I made with Mirage Esports. The CEO of PiShock persoanlly supported me also with free equipment, so thank you Lethos. It uses a shock device that will trigger when you are counter hit or punished in Tekken. Fry yourself alone or with friends. Immerse youself in pain and feel like you're in the game taking a real EWGF to the body. 

## What You Need

1. PiShock Hub x 1
2. PiShock Shocker x 1-8
3. Gaming PC x 1
4. Monitor with Supported Resolution x 1

This program revovles around the technology of PiShock's shock devices. You're going to need to by some shockers here: [https://store.pishock.com/](https://pishock.com/#/?campaign=tekkenbuns)

This program supports up to 8 simultaneous shock devices. You will need 1 PiShock Hub that will connect with the shockers you have. At minimum, you will need 1 hub and 1 shocker. Having 8 shockers is more fun though, but a bit pricy.

Once you have all your equipment, you'll need to register devices and pair through the pishock website. Just follow the direction on the packaging. The pairing process can be a bitch sometimes, so don't be surprised if you need to go through PiShock's troubleshooting steps. 

If you're PC can run Tekken 8 at 60 fps on medium settings, you should be in the green. This program will run in tandem with Tekken 8 and use computer vision to scan for the words "Punish" or "Counter" on your screen. It may make Tekken 8 drop frames at times. Making Tekken 8 a higher priority in task manager fixed it for me when I ran it on my low spec laptop.

The following monitor resolutions are supported: 1280x720 1920x1080 2560x1440 3840x2160 2560x1080 3440x1440
The program need to scale the reference image for differing resolutions to keep things running smooth, so that's why not every resolution is supported off the bat. If there's demand, I can make things more universally compatible. If your resolution isn't exact, choose the closest one and it might work.

## How to Install
Just download exe from releases page and double click it: [https://github.com/theseekingseaker/ElectricTekken/releases](https://github.com/theseekingseaker/ElectricTekken/releases)

## How to Use

Once you have all of your PiShock Shockers paired to you PiShock Hub, it's basically plug and play (hopefully). Make sure your hub is connected to you PC and your shockers are charged and turned on. Your shockers should be auto detected by the program. If it's not, try pressing "Detect Shockers".

<img width="349" height="312" alt="image" src="https://github.com/user-attachments/assets/ce49b6e6-a625-4261-aecf-c863ef65c1f6" />


Before playing, you have to do a one time calibration. On the GUI, you'll see two yellow buttons for calibration "Calibrate Left" and "Calibrate Right". Click on the calibration buttons and drag the corners of the yellow box overlay to where on the screen "Punish" and Counter" will be written on your screen. Try to make the box as small possible, but still encompass both text areas for "Punish" and "Counter". Be sure to do it for both sides. There is a preview that you can enable with a checkbox that may help you with the calibration process to check if you placed it in the correct position. If you calibrated the sides correctly, the image in the preview should encapsulate both "Punish" and "Counter" words on the screen. After you're done calibrating, turn off the preview to save resources. 

<img width="426" height="479" alt="image" src="https://github.com/user-attachments/assets/697ceaec-ed4c-49e9-b98d-ab81c093c389" />

*Don't forget to choose the corect resolution in the GUI dropdown*

Once you have both sides calibrated and the correct resolution, adjust your play settings to your liking. Keep it light for your first time. The Intensity goes from 1 to 10. Duration goes by seconds. Max 5 seconds. The last setting is the Counter Multiplier. This value will multiply the intensity and Duration by this value. I recommend keeping at 2. Counter hits hurt more. Makes sense. Immersive.

Once everything is to your preferences, press the "START" button. When this button is pressed, all of your shockers should beep. If they didn't beep, they might not be connected. In that case, try to restart them with the power button. 

At this point, you should be good to go. Play the game and see if it works.


