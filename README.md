<p align="center">
    <img alt="Dtails" src="img/dtails.png" width="200"/>
</p>
<h1 align="center">DTails</h1>

<p align="center">
  <a href="https://opensource.org/license/gpl-3-0/" title="License: GPLv3">
    <img src="https://img.shields.io/badge/License-GPLv3-red">
  <a href="https://twitter.com/BangalaXMR" title="Twitter">
  <img src="https://img.shields.io/twitter/url?url=https%3A%2F%2Ftwitter.com%2FBangalaXMR&label=Follow">
  </a>
</p>


# ℹ️ About

DTails is a tool that helps to add software in Debian based live images like Tails. DTails is not a distribution.

# ℹ️ State of the fork
- Better GUI
- Gnupg verification of the image
- Software list versioning updated
- Better debugging

## 📦 Packages requirements

```bash
sudo apt satisfy genisoimage parted squashfs-tools syslinux-utils build-essential python3-tk python3-pil.imagetk python3-pyudev python3-gnupg -y
```

## 🛠 Getting started
Clone the repository with:

```bash
git clone https://github.com/BangalaXMR/dtails
```

Once you have clone the repository and you get inside the directory. Run this to start the GUI:


```bash
sudo ./dtails.py
```

#### Why sudo?
Sudo is needed to mount the <b>.iso / .img</b> into a directory, as well to use other software. Without it, we can't use those GNU/Linux tools.

### 1. 💿 Select the Tails image
<img src="img/gui.png" width="600"/>

### 1.1 Verify GnuPG signature
<img src="img/gnupg.png" width="600"/>

### 2. 📥 / 📤 Add or remove packages
 1. Click on the checkboxes to add (Left) or remove (Right) the software you like.
 2. Click on "Build" once you are ready to build your image.

<img alt="GUI" src="img/gui2.png" width="600"/>

You can keep track in that is happening in your terminal.

<img alt="Dtails" src="https://user-images.githubusercontent.com/52879067/232882809-a968ec60-af05-4b01-9efd-be49760d76e2.png" width="700"/>


### 3. 💽 .iso vs .img
**❌ Persistence:** If you choose **.iso** image you will build an **DTail.iso** image in the same DTails directory.

**✅ Persistence:** In case you choose **.img**, you will be redirected to the 3º tab where you can choose the flash drive to install your modified OS into it.

<img alt="Dtails" src="https://user-images.githubusercontent.com/52879067/232884168-54e8653f-6262-41b0-9952-2845c62691bc.png" width="400"/>


Connect your flash drive and choose the right one. (Double check it once you select it!)

<img alt="Dtails" src="https://user-images.githubusercontent.com/52879067/232884954-36c62ea0-ac76-41a6-b6cc-6710ac90198b.png" width="400"/>

---
## 📦 List of software

To install  | To remove |
:----- | :----: |
Sparrow Wallet    | Thunderbird |
Liana Wallet   | GIMP  |
Bisq
BIP39 iancoleman
SeedTool
Border Wallets
Whirlpool GUI [🌐](https://github.com/DesobedienteTecnologico/dtails/pull/15)
Specter Desktop
MyCitadel Desktop
Bitcoin Core
Hodl Hodl and RoboSats
Mempool.space
Briar
SimpleX Chat
Rana Nostr Pubkeys mining tool
Nostr web clients (Snort & Iris)
Feather Wallet
Cake Wallet

*🌐 Chroot connects to internet to download packages

---

## **Video Spanish & English**

<a href="https://www.youtube.com/watch?v=QABz-GOeQ68"><img alt="Dtails" src="https://img.youtube.com/vi/QABz-GOeQ68/0.jpg" width="400"/></a>

