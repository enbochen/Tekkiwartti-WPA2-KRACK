# Tekkiwartti

KRACK: Key Reinstallation Attacks

![intro](../resources/pics/intro.jpg)

---

# So, what?

When: discoverd in 2016, notified vendors at July 14, 2017, publish in Public at Oct 16, 2017

Who: Mathy Vanhoef (Belgain researcher)

What: Found vulnerability of WPA2 four-way handshakes

How: Reading the code when writing another paper

Target: Any device that uses Wi-Fi is likely vulnerable (mostly Linux, Android, and OpenBSD)

---

# Details


---

# Bad News

- Change Wi-Fi password will not save you

- IoT devices rarely receive the necessary software updates to correct security issues

---

# Good News

- Attacker must be within WiFi network range

- If you are using PC (Microsoft), You're already safe

---

# What you can do ?

1. Check with device vendor if the patch is available

2. Patch all the devices that are able to be patched: router, mobiles, laptop, IoT devices etc.

3. If patch is not available, replace wireless connections with either wired connections or cellular connection

4. Replace all devices that cannot be patched

5. Place devices on separate, restricted subnets/networks/VLANs and place devices on dedicated wireless networks; then, enforce different access controls per subnet

6. Always only visit website with HTTPS

---

### What I learn ?

- Curiosity, Critical thinking, source code reading

- How to prevent these types of bugs: "Need more rigorous inspections of protocol implementations"

---

# Firmware patch status (Last Update: Oct 16, 2017)

“We’re probably still going to find vulnerable devices 20 years from now”

- macOS:warning: : macOS 10.11.1 (beta only)
- Windows:white_check_mark: : Windows 7, 8, 8.1, 10
- Linux:white_check_mark: : Ubuntu 14.04+, Arch, OpenBSD, Debian, Gentoo, Linux upstream
- Intel chipsets :white_check_mark: : Firmware updates for various chipsets
- Raspberry Pi:white_check_mark: : Jessian, Stretch fixed. Wheezy and others by October 17
- Android:warning: : Fixed at patch level "November 6, 2017." Rolls out soon to Pixel + Nexus
- Lineage OS :white_check_mark: Fixes merged, rolling out in next weekly release
- Samsung:warning: : Modern Samsung devices receive Google security patches, but older ones don't. No comment on those
- iOS:warning: : iOS 11.1, out in a few weeks
- Google WiFi:warning: : Google says a fix will roll out "soon"
- Apple Airport:warning: : Apple has not responded to requests for comment
- Cisco:white_check_mark: : Updates available across Cisco hardware
- TP Link:warning: : The company doesn't know if it's affected
- Amazon:warning: : "In the process of reviewing devices." No fix issued for Echo etc 
- IoT devices :sos: : probably patch will never reach them

https://www.windowscentral.com/vendors-who-have-patched-krack-wpa2-wi-fi-vulnerability

:white_check_mark: = Available for download and patched
:warning: = Fix pending release or in beta
:x: = No known fix
:sos: = Pray to god 


