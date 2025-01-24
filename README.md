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
- [Fixing iServices (Messages/FaceTime)](https://github.com/macOSUtilities/Realtek-WiFi-Drivers/blob/master/Fix_iServices.md)
- For Hackintoshes with **OpenCore**, use [this version](https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter).
- For Hackintoshes with **Clover**, use [this version](https://github.com/chris1111/WirelessAdapterCloverBigSur).

## Changelog:
<details>
  <summary>View all updates</summary>
- **v3.1.1:** Updated links to reflect new ownership, shorted macOS support list, cleaned up. <br>
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
- Archer T2U Plus (AC600)
- Archer T2U NANO, MINI, AC600
- Archer T3U
- Archer T3U Plus
- Archer T2U MINI V3
- Archer T2U Plus
- ArcherT4U V1, V2, V3
- Archer T9UH V1, V2
- ASUS USB AC68
- ASUS USB-N13
- ASUS USB Nano-AC53
- BrosTrend FBA_AC3
- COMFAST CF-811AC
- COMFAST CF-812AC
- Comfast CF-758F
- Comfast CF-WU810N
- Cudy WU1300S
- Cudy WU700
- Cudy WU650
- CXFTEOXK
- DLink DWA-121 N150
- DLink DWA-131 E
- DLink DWA-171 C
- DLink DWA-182 D
- DLink DWA-192 A
- EDIMAX EW-7611UCB
- EDIMAX EW-7722UTn V2
- EDIMAX_EW-7822ULC
- EDIMAX EW-7612Uan V2
- EDIMAX EW-7833UAC
- EDIMAX N300
- EDIMAX EW-7811Un (N150)
- EDUP EP-AC1689
- Fenvi AC1300 (RTL8812bu)
- FILOWA USB WiFi-RTL8812BU
- Foktech AC600 Nano
- Jensen Eagle 100-AC
- Kextech MINI USB RTL8192
- Linksys WUSB6300 V2 
- Linksys WUSB6400M
- M-Tech UW-01 USB
- Mercusys MW300UM
- Netgear A6100
- Netgear A6150
- Netgear A7000
- Netis WF2120 N Nano USB
- Plexgear AC1200
- Sitecom WLA7100
- TechKey AC1200
- TL-WN823Nv1/v2/v3
- TL-WN725Nv3
- TL-WN723Nv2/v3
- TL-WN722Nv2/v3
- TL-WN821Nv6
- TL-WN822Nv4/v5
- TENDA W311-MINI
- Tenda U3 Mini
- TENDA U12
- TRENDnet N150 Micro
- TRENDnet TEW-808UBM
- TRENDnet TEW-908UB
- UGreen CM448
- YUNCLOUD Realtek (RTL8814AU)
- ZAPO W58L (RTL881lAU)
- Zyxel NWD6602
- Zyxel NWD6605

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
