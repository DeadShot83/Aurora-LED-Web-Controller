# Aurora LED Web Controller

A beautiful Flask-based web interface for controlling LED strips via Bluetooth.  

**LED control backend:** [elk-led-controller](https://github.com/b1scoito/elk-led-controller) by [b1scoito](https://github.com/b1scoito) – thank you for the excellent Rust library!  

## Features

- 🔐 Password protection with "Remember Me" (30-day auto-login)
- 🎨 Multiple color themes (Blues, Marvel characters, Rainbow, Fire, Ocean, Police)
- ⚡ Iron Man Repulsor pulsing effect
- 🌈 Smooth color transitions and animations
- 🔁 Auto-start on reboot (systemd)
- 🔒 Optional HTTPS with self-signed certificate
- 🐳 Docker support (optional)
- 📱 Mobile-friendly responsive interface

## Credit

- **LED hardware control:** [elk-led-controller](https://github.com/b1scoito/elk-led-controller) by [b1scoito](https://github.com/b1scoito) – the core Rust binary that talks to your LEDs.
- **Web interface & integration:** Aurora project (Flask + themes + security).

## Quick Install

```bash
git clone https://github.com/yourusername/aurora-led-web.git
cd aurora-led-web
chmod +x install.sh
./install.sh
