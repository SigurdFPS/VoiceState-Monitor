# VoiceStateClient

VoiceStateClient is a lightweight desktop application that integrates with your Discord account and monitors your voice mute/unmute status in real time. It is designed to work with the VoiceState LED device via USB and enables streamers or users to visualize their voice status instantly.

---

## ✅ Features

- 🔒 Secure Discord OAuth login
- 🧠 Automatic device scan for VoiceState Box (Raspberry Pi Pico)
- 💡 LED sync for Mute / Unmute status
- 🪟 Clean, tray-based UI (minimizes to system tray)
- 🔁 Auto-launch on system startup (optional)

---

## 📦 Download & Install

1. **Head to the [Releases](https://github.com/yourusername/VoiceStateClient/releases)** page.
2. **Download the latest `.exe` installer** for Windows.
3. Run the installer and follow the one-click install flow.

Once installed, VoiceStateClient will be available in your Start Menu and system tray.

---

## 🔗 Connect Discord Account

1. Launch the app.
2. Click **Connect Discord**.
3. Your browser will open and request permission to authorize VoiceStateClient.
4. After success, return to the app – your profile will load automatically.

---

## 🤖 Add the Bot to Your Server

To have your Discord mute/unmute status monitored, **install the companion bot** into the server you want to track:

👉 [Install Bot to Server](https://discord.com/oauth2/authorize?client_id=1378084297121988669)

Make sure:
- You have permission to manage bots on the server
- The bot has access to **voice state** permissions

---

## 💡 Device Integration (VoiceState Box)

VoiceStateClient auto-detects the connected **VoiceState Box (e.g., Raspberry Pi Pico)** over USB:

- Ensure it is plugged in and uses the correct firmware
- The app will show ✅ connection success and sync the mute state

If not found, click **Scan for VoiceState Box**.

---

## 📝 Notes

- This application stores config and token data locally in the user’s profile directory.
- `config.json` and `state.json` are created automatically after first launch.
- All communication uses secure local sockets and no data is stored externally.

---

## ❓ Troubleshooting

- Make sure no other app is using the serial port
- Check Windows Device Manager for the correct COM port
- Re-run the installer if the app fails to launch

---

## 📄 License

MIT License © [SigurdFPS](https://github.com/yourusername)
