# 🐝 BuzzAdv & BuzzGuardianLAB Suite
**FDF Certified™ BLE Security & Learning Toolkit**  
Secret Sauce XL, Triple Stack, Buzzanator Drip Edition 🚀

---

## 🔥 What is BuzzAdv?
BuzzAdv is the **one-of-one BLE Advertising Packet Decoder & Guardian Suite**.  
It cross-maps every packet field against the official **Bluetooth Assigned Numbers**, detects **spoof/mismatch anomalies**, and teaches you BLE in real-time.

Runs everywhere:
- 🖥️ Linux / Mac / Windows
- 📱 Termux / Android
- 🌐 Web Dashboards (BuzzRadar)
- 📦 Mobile App (Expo wrapper)

---

## ✨ Features
- `buzzadv decode <hex>` → Decode raw advertising packet
- `buzzadv scan` → Live BLE scanner
- `buzzadv watch` → Guardian spoof-detect (Appearance vs Services, Company ID mismatches)
- `buzzadv extract` → Pull fields (names, UUIDs, manufacturer blocks) → export CSV/JSON
- `buzzadv replay` → Replay captured ADV (lab/testing only)
- `buzzadv inject` → Emulate profiles (iBeacon, Eddystone, etc.)
- `buzzadv guard` → Rule engine (guardian.yaml)
- `buzzadv learn` → FDF University mode (tutorials + quizzes)
- `buzzadv export --pcap` → Parse Wireshark/nRF Sniffer logs
- `buzzadv viz` → CLI/ASCII or web visualization

---

## 🛠️ Installation
### Termux / Linux / Mac / Windows
```bash
git clone https://github.com/figuripv6o/buzzadv.git
cd buzzadv
pip install -e .
buzzadv --
