# Realtek Wi-Fi Adapter Drivers for macOS

## macOS drivers for Realtek 802.11n and 802.11ac Wi-Fi adapters.

### [Download the latest release](https://github.com/kingkwahli/RTK_USB-WiFi_Drivers_macOS/releases/)
### Only supports macOS 10.15 (Catalina) and newer

### Compatibility:
- Only works on Intel-based Macs.
- **Not compatible with Apple Silicon (M1, M2, M3, M4).**

### Special Instructions:
- For **macOS Sequoia**, [Disable Gatekeeper](https://github.com/chris1111/Disable-Gatekeeper).
- For **macOS 11 (Big Sur) and newer**, you must disable SIP. Reboot into Recovery (Cmd+R while rebooting), open Terminal from the Utilities menu, and run `csrutil disable`.

### Additional Resources:
- [Fixing iServices (Messages/FaceTime)](https://github.com/macOS/Realtek-WiFi-Drivers/blob/master/Fix_iServices.md)
- For Hackintoshes with **OpenCore**, use [this version](https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter).
- For Hackintoshes with **Clover**, use [this version](https://github.com/chris1111/WirelessAdapterCloverBigSur).

## Changelog:
<details>
  <summary>View all updates</summary>
  
- **v3.1:** Fixed spelling/grammer errors, cleaned up background and other images <br>
- **v3.0.2:** Updated README, created discussion <br>
- **v3.0.1:** Revamped README <br>
- **v3.0:** Reduced package size and updated background. <br>
- **v2.6:** Updated StatusBarApp background. <br>
- **v2.5.1:** Listed supported adapters in README. <br>
- **v2.5:** Updated program background. <br>
- **v2.4:** Improved Helper tools. <br>
- **v2.3:** No longer requires Agents and Daemons. <br>
- **v2.2:** Added support for macOS Ventura 13.<br>
- **v2.1:** Added support for macOS Big Sur 11. <br>
- **v2.0:** Introduced a blue Wi-Fi icon, reminiscent of Big Sur's.
  
</details>

## Supported Wi-Fi Adapters:
<details>
  <summary>View known, working adapters</summary>

- Alfa AWUS036AC
- Alfa AWUS036ACH
- ASUS USB AC68, USB-N13, USB Nano-AC53
- BrosTrend FBA_AC3
- COMFAST CF-811AC, CF-812AC, CF-WU810N
- Cudy WU1300S, WU700, WU650
- DLink DWA-121, DWA-131E, DWA-182, DWA-192
- EDIMAX EW-7611UCB, EW-7722UTn V2, EW-7811Un (N150)
- Fenvi AC1300 (RTL8812bu)
- Linksys WUSB6300 V2, WUSB6400M
- Netgear A6100, A6150, A7000
- TP-Link TL-WN823Nv3, TL-WN725Nv3
- TP-Link Archer T2U Plus (AC600)
- TP-Link Archer T3U, T3U Plus
- TP-Link Archer T2U Nano/Mini/AC600
- TRENDnet TEW-808UBM, TEW-908UB

[Report additional working adapters here](https://github.com/macOSUtilities/Realtek-WiFi-Drivers/discussions/1).

</details>

## Instructions for configuring the Adapter:
1. Select **System Settings** from the Launchpad or the Apple menu.
2. Select **Network** from the side panel
3. From **Other Services**, select **802.11ac WLAN Adapter** then **Details…**
4. Configure any settings, such as IP Address, DNS, etc.
5. Click the **Ok** button. Enter your password if necessary.
Settings configured.

## Wi-Fi Speed Tests:
- In macOS Monterey or newer, you can run the command `networkquality` for speed tests.
- You can also use [Speedtest](https://speedtest.net) or [Fast](https://fast.com/).

## Disclaimer:
These drivers (and their creator) are not responsible for any damage to your computer.
I never knew this would be needed to say, but these drivers DO NOT work on iPhone/iPad.
Credits for the original project go to chris1111
### Video Tutorials:
- [How to Install on macOS Monterey](https://youtu.be/YqZAy8jntow)
- [Fix if SIP is not disabled](https://youtu.be/lA1V6dmsq24)
