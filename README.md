# Apple.Remote.crash
collect crash reports for every submitted version of your app. Crash reports automatically contain identifiable symbol information if you include symbol information when submitting a build to the App Store
# shankar patel simi
Tool-CVE-2023-4407
Crashes any macOS High Sierra or iOS 11 device that is on the same WiFi network

Just a small Tool that uses a public 'heap buffer overflow vulnerability' (CVE-2018-4407) and makes it easier to exploit whole networks.


## Requirements
- MacOS
- Python installed
- Scapy installed (`pip install scapy`)

## Basics
Sends a malicious ICMP packet to the IP address of the target device

## Works on
- Apple iOS 11 and earlier: all devices (upgrade to iOS 12)
- Apple macOS High Sierra, up to and including 10.13.6: all devices (patched in  security update 2018-001 )
- Apple macOS Sierra, up to and including 10.12.6: all devices (patched in  security update 2018-005 )
- Apple OS X El Capitan and earlier: all devices

## Notes
- Port Feature is useless
- Network Scan only adds Devices from the ARP cache (devices that the mac communicated with since last reboot)  
A short networkscan with any IP Scanner is recommended before pressing the button

## Features

**Extra Ping Methods:**  
Sometimes Devices don't react to the malicious packet. That is fixed when it recieves a valid ICMP packet (ping) before


- Extra Ping Method 1:  
Concurrently pings alls devices in the Background (only for a couple of IPs! - With more IPs, nothing works)

- Extra Ping Method 2:  
Pings every Device once before sending the malicious ICMP packet (might be slow)

## Screenshot
![alt text](https://raw.githubusercontent.com/anonymouz4/Apple-Remote-Crash-Tool-CVE-2023-4407/master/Screenshot.png)

# Contact
* [Twitter](https://www.twitter.com/shankarpatels9) - _shankarpatels9
* [Instagram](https://www.instagram.com/shankarpatel__simi) - shankarpatel__simi
# Authors :
* facebook  : shankar patel simi
* gmail     : sp922741@gmail.com
* instagram : shankarpatel__simi
* Twitter   : shankarpatels9
* SocialBox : shankar simi
