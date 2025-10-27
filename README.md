# 🐧 Linux Useful Tools & Tricks

A curated collection of powerful command-line tools and applications to supercharge your Linux experience.

## 📑 Table of Contents

- [Media & Downloads](#-media--downloads)
- [Image & Graphics](#-image--graphics)
- [Document Processing](#-document--processing)
- [File Management & Sync](#-file-management--sync)
- [System Monitoring](#-system-monitoring)
- [Network Tools](#-network-tools)
- [Development Tools](#-development-tools)
- [Text Processing](#-text-processing)
- [Security & Privacy](#-security--privacy)
- [Productivity](#-productivity)

---

## 🎬 Media & Downloads

### yt-dlp
Download videos from YouTube and 1000+ other sites with advanced features.
```bash
sudo apt install yt-dlp
yt-dlp https://www.youtube.com/watch?v=VIDEO_ID
```

### ffmpeg
Complete solution for recording, converting, and streaming audio and video.
```bash
sudo apt install ffmpeg
ffmpeg -i input.mp4 output.avi
```

### mpv
Lightweight, powerful media player with minimal interface.
```bash
sudo apt install mpv
mpv video.mp4
```

### aria2
Ultra-fast download utility supporting HTTP/HTTPS, FTP, BitTorrent.
```bash
sudo apt install aria2
aria2c -x 16 https://example.com/file.iso
```

---

## 🎨 Image & Graphics

### GIMP
Professional open-source image editor (Photoshop alternative).
```bash
sudo apt install gimp
```

### ImageMagick
Command-line image manipulation toolkit for converting, editing, and composing images.
```bash
sudo apt install imagemagick
convert input.jpg -resize 50% output.jpg
```

### Inkscape
Professional vector graphics editor (Illustrator alternative).
```bash
sudo apt install inkscape
```

### flameshot
Powerful screenshot tool with annotation features.
```bash
sudo apt install flameshot
flameshot gui
```

---

## 📄 Document Processing

### Pandoc
Universal document converter supporting Markdown, PDF, HTML, and more.
```bash
sudo apt install pandoc
pandoc input.md -o output.pdf
```

### pdftohtml
Convert PDF files to HTML format.
```bash
sudo apt install poppler-utils
pdftohtml input.pdf output.html
```

### pdftk
PDF toolkit for merging, splitting, and manipulating PDF files.
```bash
sudo apt install pdftk
pdftk file1.pdf file2.pdf cat output merged.pdf
```

### LibreOffice
Complete office suite (Microsoft Office alternative).
```bash
sudo apt install libreoffice
```
### Glow
Terminal markdown reader 

```bash
sudo snap install glow
```

---

## 📁 File Management & Sync

### rsync
Fast, versatile file copying and synchronization tool.
```bash
sudo apt install rsync
rsync -avz source/ destination/
```

### Syncthing
Continuous file synchronization between devices without cloud storage.
```bash
sudo apt install syncthing
syncthing
```

### rclone
Command-line program to sync files and directories to cloud storage.
```bash
sudo apt install rclone
rclone sync /local/path remote:path
```

### ncdu
NCurses disk usage analyzer for finding space hogs.
```bash
sudo apt install ncdu
ncdu /home
```

### fzf
Fuzzy finder for the command line - search files, history, processes.
```bash
sudo apt install fzf
# Press Ctrl+R for command history search
```

---

## 📊 System Monitoring

### htop
Interactive process viewer and system monitor.
```bash
sudo apt install htop
htop
```

### btop
Resource monitor with beautiful interface and customization.
```bash
sudo apt install btop
btop
```

### iotop
Monitor disk I/O usage by process.
```bash
sudo apt install iotop
sudo iotop
```

### glances
Cross-platform system monitoring tool with web interface.
```bash
sudo apt install glances
glances
```

### neofetch
Display system information with ASCII art.
```bash
sudo apt install neofetch
neofetch
```

---

## 🌐 Network Tools

### nmap
Network exploration and security auditing tool.
```bash
sudo apt install nmap
nmap -sP 192.168.1.0/24
```

### wireshark
Network protocol analyzer for troubleshooting and analysis.
```bash
sudo apt install wireshark
```

### curl
Transfer data with URLs, supporting numerous protocols.
```bash
sudo apt install curl
curl -O https://example.com/file.zip
```

### netcat (nc)
Networking utility for reading/writing network connections.
```bash
sudo apt install netcat
nc -l 8080
```

### speedtest-cli
Test internet bandwidth using speedtest.net.
```bash
sudo apt install speedtest-cli
speedtest-cli
```

---

## 💻 Development Tools

### git
Distributed version control system.
```bash
sudo apt install git
git clone https://github.com/user/repo.git
```

### tmux
Terminal multiplexer for managing multiple terminal sessions.
```bash
sudo apt install tmux
tmux
```

### Docker
Platform for developing, shipping, and running applications in containers.
```bash
sudo apt install docker.io
docker run hello-world
```

### VSCodium
Open-source build of VS Code without Microsoft telemetry.
```bash
# Installation varies by distribution
```

### jq
Lightweight command-line JSON processor.
```bash
sudo apt install jq
cat data.json | jq '.key'
```

---

## 📝 Text Processing

### vim/neovim
Highly configurable text editor.
```bash
sudo apt install neovim
nvim file.txt
```

### bat
Cat clone with syntax highlighting and Git integration.
```bash
sudo apt install bat
bat file.py
```

### ripgrep (rg)
Extremely fast grep alternative for searching code.
```bash
sudo apt install ripgrep
rg "search term" /path/to/directory
```

### sed
Stream editor for filtering and transforming text.
```bash
sed 's/old/new/g' input.txt > output.txt
```

### awk
Pattern scanning and text processing language.
```bash
awk '{print $1}' file.txt
```

---

## 🔒 Security & Privacy

### fail2ban
Ban hosts that cause multiple authentication errors.
```bash
sudo apt install fail2ban
sudo systemctl enable fail2ban
```

### ufw
Uncomplicated Firewall - easy-to-use firewall management.
```bash
sudo apt install ufw
sudo ufw enable
```

### gpg
Encrypt and sign data and communications.
```bash
sudo apt install gnupg
gpg --encrypt --recipient user@example.com file.txt
```

### ClamAV
Open-source antivirus engine.
```bash
sudo apt install clamav
sudo freshclam
clamscan -r /home
```

---

## ⚡ Productivity

### tldr
Simplified man pages with practical examples.
```bash
sudo apt install tldr
tldr rsync
```

### zoxide
Smarter cd command that learns your habits.
```bash
# Installation varies
z documents
```

### Timeshift
System restore utility creating filesystem snapshots.
```bash
sudo apt install timeshift
```

### ranger
Console file manager with vi key bindings.
```bash
sudo apt install ranger
ranger
```

---

## 🤝 Contributing

Feel free to submit pull requests to add more useful tools or improve existing descriptions!

## 📜 License

This repository is licensed under the MIT License.

## ⭐ Star this repo if you find it useful!
