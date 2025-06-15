
# CEDZEE Search Port Linux 

**Version adaptée pour Arch Linux** du navigateur Cedzee original

### Installation des dépendances

```bash
sudo pacman -S python python-pyqt6 python-pyqt6-webengine
```

### installer cedzee-browser

```bash
sudo pacman -U cedzee-browser-1.0-1-any.pkg.tar.zst
```

### Créer le paquet Arch (ne sert que si vous souhaitez modifier l'application)

```bash
makepkg -si
```
