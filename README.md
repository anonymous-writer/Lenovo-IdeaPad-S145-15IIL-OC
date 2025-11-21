# Lenovo IdeaPad S145-15IIL – Hackintosh Guide (Big Sur → Ventura)

**Modell:** Lenovo IdeaPad S145-15IIL  
**CPU:** Intel Core i5‑1035G1  
**GPU:** Intel UHD Graphics (10th Gen)  
**Bootloader:** OpenCore  
**Kompatible macOS-Versionen:** Big Sur bis Tahoe

---
## 🔗 Relevante Links
- **Geräteseite Lenovo:** https://pcsupport.lenovo.com/us/en/products/laptops-and-netbooks/ideapad-s-series-netbooks/s145-14iil
- **Intel i5‑1035G1 Specs:** https://www.intel.com/content/www/us/en/products/sku/196603/intel-core-i51035g1-processor
- **OpenCore Bootloader:** https://github.com/acidanthera/OpenCorePkg
- **Intel Wi‑Fi 6E AX210 Specs:** https://www.intel.de/content/www/de/de/products/sku/204836/intel-wifi-6e-ax210-gig/specifications.html

---
## 📁 EFI-Ordner
Funktioniert mit macOS **Big Sur bis Ventura**.  
Bei Installation über macOS‑USB‑Stick im `config.plist`:
```
Misc → Security → SecureBootModel → Disabled
```

---
## 🛠️ Hardware‑Hinweise
### WLAN-Karte
Empfohlen:
- **Intel Wi-Fi 6E AX210** (benötigt passende Kexts)
- oder **Broadcom BCM94360CS2** (nativ unter macOS)

---
## ✅ Funktioniert vollständig
- Intel UHD iGPU
- USB‑Ports
- Sonix‑Webcam (Big Sur → Tahoe)
- Helligkeitssteuerung + Regler
- Akkustatus & Prozentanzeige
- Sleep / Wake
- ELAN0633‑Touchpad (mit VoodooI2C + Gesten)
- WLAN (Broadcom oder AX210)
- Lautsprecher, Kopfhöreranschluss, Mikrofon
- Internes Mikrofon
- Apple‑Dienste: iMessage, FaceTime, iCloud, Apple Watch Unlock
- Bluetooth
- SD‑Kartenleser
- HibernateMode 25

---
## ❌ Funktioniert nicht
- **HDMI‑Ausgang**

---
## 🖼️ Screenshots

### Systeminformationen
![About This Mac – System Info](https://raw.githubusercontent.com/anonymous-writer/Lenovo-IdeaPad-S145-15IIL/master/Pictures/System.png)

### macOS Tahoe Desktop
![macOS Tahoe Desktop](https://raw.githubusercontent.com/anonymous-writer/Lenovo-IdeaPad-S145-15IIL/master/Pictures/Tahoe.png)

### OpenCore Boot Picker
![OpenCore Boot Picker](https://raw.githubusercontent.com/anonymous-writer/Lenovo-IdeaPad-S145-15IIL/master/Pictures/Startbildschierm.png)

### YogaSMC – Batterie & Lüftersteuerung
![YogaSMC Battery & Fan Control](https://raw.githubusercontent.com/anonymous-writer/Lenovo-IdeaPad-S145-15IIL/master/Pictures/YogaSMC.png)

### USB‑Port‑Mapping
![USB Ports Mapping](https://raw.githubusercontent.com/anonymous-writer/Lenovo-IdeaPad-S145-15IIL/master/Pictures/USB-Ports.png)

---
## 🎥 Video – HibernateMode 25
[![HibernateMode 25 Demo](https://img.youtube.com/vi/zcpLceNhjyA/0.jpg)](https://www.youtube.com/watch?v=zcpLceNhjyA)
