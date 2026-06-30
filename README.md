# AirPulse Platforms

<img width="880" height="495" alt="AirPulseOpSys"
     src="https://github.com/user-attachments/assets/56df1d25-4bc5-44d7-85c4-9f5200d10bf5" />

# AirPulse Releases

Official binary releases for Feedline Labs AirPulse.

This repository contains release packages for:

- Windows Desktop (x64)
- Raspberry Pi (ARM64)
- Linux (x64)

Source code is not included.

## Downloads

Download the latest version from the Releases page.

## Install

Raspberry PI: https://feedlinelabs.com/airpulse-raspberry-pi-setup.html

Linux : https://feedlinelabs.com/airpulse-linux-setup.html

macOS : https://feedlinelabs.com/airpulse-macos-setup.html

## Accessing the Control Panel

This Computer
http://localhost:5050/control-panel.html

Network
http://192.168.1.224:5050/control-panel.html (IP will vary, see below)

Hostname
http://airpulse-node.local:5050/control-panel.html   (when available)

## Find Your AirPulse.Node IP Address

### Windows:

Open **Command Prompt** and run:

```text
ipconfig
```

Look for the **IPv4 Address** under your active Wi-Fi or Ethernet adapter:

```text
IPv4 Address. . . . . . . . . . . : 192.168.1.224
```

#### Raspberry Pi / Linux:

Run:

```bash
hostname -I
```

#### macOS:

Open **Terminal** and run:

```bash
ipconfig getifaddr en0
```

## Documentation

https://feedlinelabs.com

## Support

Join the Feedline Labs Discord:

https://discord.com/invite/YEtb6c9d6b
