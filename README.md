# Realtek Wi-Fi USB Drivers for macOS

## macOS drivers for Realtek 802.11n and 802.11ac USB Wi-Fi adapters.

### [Download the latest version](https://github.com/kingkwahli/RTK_USB-WiFi_Drivers_macOS/releases/)

### Supported macOS Versions:
- macOS 15 (Sequoia)
- macOS 14 (Sonoma)
- macOS 13 (Ventura)
- macOS 12 (Monterey)
- macOS 11 (Big Sur)
- macOS 10.15 (Catalina)

**Note:** Do not use on other versions!

### Compatibility:
- Only works on Intel-based Macs.
- **Not compatible with Apple Silicon (M1, M2, M3, M4).**

### Special Instructions for macOS Versions:
- For **macOS Sequoia**, [Disable Gatekeeper](https://github.com/chris1111/Disable-Gatekeeper).
- For **macOS Big Sur and newer**, you must disable SIP. Reboot into Recovery (Cmd+R while rebooting), open Terminal from the Utilities menu, and run `csrutil disable`.

### Additional Resources:
- [Fixing iServices (Messages/FaceTime)](https://github.com/kingkwahli/RTK_USB-WiFi_Drivers_macOS/tree/master/blob/master/Fix_Apple_Services.md)
- For Hackintoshes with **OpenCore**, use [this guide](https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter).
- For Hackintoshes with **Clover**, use [this guide](https://github.com/chris1111/WirelessAdapterCloverBigSur).

## Changelog:
<details>
  <summary>View all updates</summary>
- **12 Oct 2024:** Revamped README
- **12 Jul 2024:** Reduced package size and updated background.
- **11 Jul 2024:** Updated StatusBarApp background.
- **16 Jan 2024:** Listed supported adapters in ReadMe.
- **02 Jul 2023:** Updated program background.
- **15 Dec 2022:** Improved Helper tools.
- **02 Nov 2022:** No longer requires Agents and Daemons.
- **12 Jun 2022:** Added support for macOS Ventura 13.
- **15 Sep 2021:** Adapted for macOS Big Sur 11.
- **29 Nov 2020:** Introduced a blue Wi-Fi icon similar to Big Sur.

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

[Report additional working adapters here](https://github.com/kingkwahli/RTK_USB-WiFi_Drivers_macOS/discussions).

</details>

## Instructions for configuring the Adapter:
1. Select the **System Settings** from the Launchpad or the Apple icon menu.
2. Select **Network** from the side panel
3. From **Other Services**, select **802.11ac WLAN Adapter** then **Details…**
4. Configure any settings.
5. Click the **Ok** button. Enter your password if necessary.
Settings configured.

## Wi-Fi Speed Tests:
- Starting with macOS Monterey, you can run the command `networkquality` for speed tests.
- You can also use [Speedtest](https://speedtest.net) or [Fast](https://fast.com/)

## Disclaimer:
These drivers (and their creator) are not responsible for any damage to your machine.

### Video Tutorials:
- [How to Install on macOS Monterey](https://youtu.be/YqZAy8jntow)
- [Fix if SIP is not disabled](https://youtu.be/lA1V6dmsq24)
