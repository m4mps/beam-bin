# BeamAI Installation Guide

### Windows
```text
You can find the official Windows installer under "Releases".
```

### Arch Linux
```bash
git clone https://github.com/m4mps/beam-bin
cd beam-bin
makepkg -si
```

### Ubuntu / Debian
```bash
curl -L -o beamai.deb "https://github.com/m4mps/beam-bin/raw/main/beamai_0.1.0_amd64.deb" && sudo apt install ./beamai.deb && rm beamai.deb
```

### Fedora
```bash
sudo dnf install "https://github.com/m4mps/beam-bin/raw/main/beamai-0.1.0-1.x86_64.rpm"
```

### Universal Linux AppImage
```bash
curl -L -o beamai.AppImage "https://github.com/releases/download/v0.1.0/beamai_0.1.0_amd64.AppImage"
chmod +x beamai.AppImage
./beamai.AppImage &
```

Have Fun!
