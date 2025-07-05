# GitHub Copilot Lamp
A fun and playful lamp to match the energy of [GitHub Copilot](https://github.com/features/copilot). It's 3d printable, fairly easy to assemble, WiFi connected and powered by [WLED](https://kno.wled.ge/) and touch!

> This project was inspired by the original [Octolamp](https://github.com/martinwoodward/octolamp). Go check it out!

![](docs/copilot-lamp.jpg)

## How to Use
If you received your lamp prebuilt, is has already been configured and is ready to use. Simply plug it in with a USB cable and power brick with at least 1 amp. The lamp will turn on with an "aurura" like green effect.

### How to Turn on/off
The white spot between the goggles is a touch sensor and provides basic control the lamp. For more advanced control, you can use the WLED app or web interface!

- Automatically turns on at 9am CST.
- Automatically turns off at 5pm CST.

| Single Press | Double Press | Long Press |
| - | - | - |
| Slow Fade Green | Fast Random Rainbow | Off |
| ![](docs/README/touch-single.gif) | ![](docs/README/touch-double.gif) | ![](docs/README/touch-hold.gif) |

### Connect to WiFi
Want full control over your lamp? Connect it to your WiFi network! (2.4ghz only)
If not connected to an existing wifi, it will broadcast a tempory wifi network for setup.

1. On your phone or computer, search for the wifi network `copilot-lamp` and connect to it.
    - Default password is `copilot-lamp` or `wled1234`.
1. Wait a moment and a temporary login-style web browser will appear. If no browser appears, open a web browser navigate to http://copilot-lamp.local.
1. In the top right, click the **Config** gear icon to open the settings menu.
1. Select **WiFi Setup**.
1. Enter you home's wifi name and password. Click **Save & Connect**. Wait a moment for the lamp to restart.
1. Reconnect your phone or computer to your home wifi.
1. Now when connected to your home wifi, you can use the WLED app.
    - [iOS App](https://apps.apple.com/us/app/wled/id1475695033)
    - [Android App](https://play.google.com/store/apps/details?id=com.aircoookie.WLED)
    - Alternately, the lamp can still be accessed in  a web browser by navigating to http://copilot-lamp.local.

<div>
<img src="docs/README/connect-wifi-1.png" width="24%">
<img src="docs/README/connect-wifi-2.png" width="24%">
<img src="docs/README/connect-wifi-3.png" width="24%">
<img src="docs/README/connect-wifi-4.png" width="24%">
</div>

### Change eye color

1. Using a screwdriver, insert the end through the holes in the back of the lamp.  
    <img src="docs/README/eyes-change-1.jpg" width="300px">

1. Continue to push and the eye insert will pop forward.  
    <img src="docs/README/eyes-change-2.jpg" width="300px">

1. Insert the other colored eyes!

### Change helmet color (faceplate)

1. Grip the top of the mask and gently push into the white space of the goggles. You will feel the connectors pop out.  
    <img src="docs/README/faceplate-change-1.jpg" width="300px">

1. Flip the lamp over, and repeat on the other side. Once disconnected, slide the faceplate off.

1. Apply the new faceplate!

## Troubleshooting

### Can't connect to WiFi.
If you aren't able to connect to 'copilot-lamp' or you locked yourself out by entering bad wifi information, you can update the wifi information at the WLED website.

1. Connect the device to your computer using a USB cable.
1. Click 'Install' button. It will detect the lamp already has WLED installed and provide options.
1. Select 'Change WI-FI' and it will scan for nearby options.
1. Enter your wifi password and wait a moment.
1. Click 'Visit Device' and it will navigate to the webpage view.

# Build your own 🤓
That's cool and all, but how do I make one?!  
Check out the [build your own](docs/build-your-own.md) page for a step-by-step guide. 🧑‍🚀

Making it for someone else? How kind of you! 💚 Check out the [gift a friend](docs/gift-a-friend.md) page to create an awesome unboxing experience! 🤩
