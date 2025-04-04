# Virtual CSP - Digital Signing Made Easy

## What is Virtual CSP?
Virtual CSP (Cryptographic Service Provider) is a tool that lets you sign documents digitally on your Windows computer without needing a USB Token. It connects directly to a server (HSM) via an API, allowing you to sign files in apps like Word, Acrobat, or Tax/Customs systems right from your desktop.

## Key Features
- **No USB Token Needed**: Sign securely without physical devices.
- **Works with Popular Apps**: Compatible with MS Office, Acrobat Reader, and more.
- **Simple to Use**: Just install, connect, and sign—like using a USB Token.

## How It Works
1. Install Virtual CSP on your Windows PC (tested on Win 7/10/11).
2. Run the `ClienToolvCSP.exe` tool to fetch your certificate from the server HSM.
3. Open your app, select the certificate, enter a PIN, and sign!

## Demo Setup
- **Server**: Tomcat 8 with the provided `.war` package.
- **Config**: Adjust the P12 file path and password in `config.json` (in Tomcat's `Conf` folder).
- **APIs**:
  - `getbase64cert`: Get the certificate in base64 format.
  - `signdata`: Sign your data.

> Note: This is a demo using a P12 file. In real use, it connects to an HSM.

## Installation
1. Download and install the Virtual CSP package.
2. Run `ClienToolvCSP.exe`, click "Connect to System" to verify the certificate.
3. Start signing in your favorite apps!

## Why Use Virtual CSP?
Perfect for businesses or individuals who want a modern, flexible way to sign digitally, especially if you already have an HSM but struggle to integrate it with various software.

## Contact
[dk.nam855@gmail.com]!# virtual-CSP
