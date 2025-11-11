# FMDXConnector

A WebSocket connector for TEF Logger communication with FMDX Webserver (Compatible from Android 8)


![Bild1](https://github.com/user-attachments/assets/d123534b-9964-4f3f-87bb-3642df81bae3)

## Version 1.1

- Integrated display and direct download of beta versions (Activate in the menu!)
- Display of changes in the update dialog
- URDS Map now uses the same map set as the TX Map and is therefore capable of offline use
- CSV files now contain extended TX data
- The Copy Button under URDS Options now has an export function and also allows sharing of URDS files
- A new import button under URDS Options now allows you to import CSV files
- You can now also send CSV files directly into the app using the send/share command
- Info button with TX location selection fixed

## Installation notes:

1. If the scanner plugin is installed on the web server, make sure it is version 3.9 or higher (This is required for the Search << >> and Auto Scan functions!)
2. [Download](https://github.com/Highpoint2000/FMDXConnector/raw/refs/heads/main/FMDXConnector_1.0.apk) the latest apk file 
3. Install the apk on your smartphone with paket manager
4. Check your energy saving settings

## Tested on:

- Samsung Galaxy S7 Edge with Android 8
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

- Address entry with port specification can be done using IP address or domain name, e.g.: highpoint2000.selfhost.de:9080
- The communication key for the scanner plugin is located in the scanner.json file on the web server or is displayed in the console upon startup. Without this key, the auto-scan cannot be started or stopped.
- The server connection is activated via the Connect button. A green status indicates a successful connection. The server information will now be forwarded to the TEF Logger app.

## Contact

If you have any questions, would like to report problems, or have suggestions for improvement, please feel free to contact me! You can reach me by email at highpoint2000@googlemail.com. I look forward to hearing from you!

<a href="https://www.buymeacoffee.com/Highpoint" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

<details>
<summary>History</summary>
