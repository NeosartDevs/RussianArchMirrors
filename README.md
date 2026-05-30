Список Arch зеркал бесперебойно работающих в России.

Установка:
```bash
sudo cd /etc/pacman.d
sudo rm mirrorlist
sudo curl -O https://raw.githubusercontent.com/NeosartDevs/RussianArchMirrors/refs/heads/main/mirrorlist
sudo pacman -Syu
```
