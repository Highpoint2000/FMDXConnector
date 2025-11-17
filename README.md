# FMDXConnector
A WebSocket connector for TEF Logger communication with FMDX Webserver (Compatible from Android 8)

<img width="836" height="587" alt="image" src="https://github.com/user-attachments/assets/53d13aa3-393e-48b0-a7e4-082152e09e52" />



## Version 2.0 (Please uninstall version 1.0 first!)

- Audio playback added
- Integration of the FMFX server map for direct selection and saving of web servers (globe button / save via + button)
- Dark design for older devices

## Installation notes:

1. If the scanner plugin is installed on the web server, make sure it is version 3.9 or higher (This is required for the Search << >> and Auto Scan functions!)
2. [Download](https://github.com/Highpoint2000/FMDXConnector/raw/refs/heads/main/FMDXConnector_2.0.apk) the latest apk file 
3. Install the apk on your smartphone with paket manager
4. Check your energy saving settings

## Tested on:

- Samsung Galaxy S7 Edge with Android 8
- Sasmung Galaxy Tab A with Android 8.1
- Samsung Galaxy S8 with Android 9 / OneUI 1.0 (Chrome update required -> external APK!)
- Samsung Galaxy A8 (2018) with Android 9 / OneUI 1.0 (Chrome update required -> external APK!)
- Samsung Galaxy A6 with Android 10 / OneUI 2.0
- Samsung Galaxy Tab A 10.5 (2018) with Android 10 / OneUI 2.1
- Samsung Galaxy A20e with Android 11 / OneUI 3.1
- Samsung Galaxy A12 with Android 12 / OneUI 4.1
- Samsung Galaxy Tab A7 10.4 with Android 12 / OneUI 4.1
- Samsung Galaxy A51 with Android 13 / OneUI 5.1
- Samsung Galaxy A13 with Android 14 / OneUI 6.1
- Samsung Galaxy Tab A9+ with Android 15 / OneUI 7.0
- Samsung Galaxy S24 Ultra with Android 16 / OneUI 8.0

## Notes:

- Servers can be connected by directly entering the URL/domain:port (e.g., https://highpoint.fmtuner.org or highpoint2000.selfhost.de:8080) or by selecting https://servers.fmdx.org (button with the globe icon)
- The server connection is activated via the "Connect" button. A green status indicates a successful connection (TEF [FMDX #X]). The server information is then forwarded to the TEF Logger app
- Once a successful connection is established, the audio stream also starts, and the button at the top changes from the play to the stop symbol. Pressing the stop button stops the stream
- Servers can be saved using the "+" button (swipe left or use the arrow on the right; #1, #2, etc. will then appear)
- The web server administrator password is required to start/stop the automatic scan function. The search function << >> does not require a password. However, the scanner plugin version 3.9 or later must be installed
- The current values ​​in server box #0 can be deleted via the X in the upper left corner. This is useful if you want to configure your own server. For all other server boxes (#1, #2, #3, etc.), the X deletes the box

## Contact

If you have any questions, would like to report problems, or have suggestions for improvement, please feel free to contact me! You can reach me by email at highpoint2000@googlemail.com. I look forward to hearing from you!

<a href="https://www.buymeacoffee.com/Highpoint" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

<details>
<summary>History</summary>

### Version 1.0

- FMDX web servers can be directly connected to the TEF Logger app (https://github.com/highpoint2000/TEFLoggerapp)
- Unlimited number of web server profiles can be added
- Profile selection via swipe function or left/right buttons
- Integrated system logging function
- Optional control of the autoscan function via admin passwort and scanner plugin available from version 3.9 (https://github.com/Highpoint2000/webserver-scanner)
