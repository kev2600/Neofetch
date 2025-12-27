# Neofetch & Fastfetch — Manual Installation Guide

Neofetch and Fastfetch are lightweight system‑information tools that display your OS, hardware, and theme details in a clean, aesthetic format. They’re commonly used for screenshots, ricing, and quick diagnostics.

---

## 📦 Neofetch (Manual Install)

Neofetch is no longer actively maintained, but many users still prefer its classic look.

### Install
```bash
git clone https://github.com/dylanaraps/neofetch
cd neofetch
sudo make install
```

### Run
```bash
neofetch
```

---

## ⚡ Fastfetch (Recommended)

Fastfetch is a modern, actively maintained alternative to Neofetch. It’s faster, more customizable, and supports more modules.

### Fedora / DNF
```bash
sudo dnf install fastfetch
```

### Ubuntu / Debian
```bash
sudo apt install fastfetch
```

### Run
```bash
fastfetch
```

---

## 📝 Notes
- Both tools work out of the box with no configuration required.
- Fastfetch supports custom configs at:  
  `~/.config/fastfetch/config.jsonc`
- Neofetch configs live at:  
  `~/.config/neofetch/config.conf`

---

## 📸 Example Output
After installation, simply run the command and enjoy the system summary in your terminal.

