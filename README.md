An operating system that is:
- fast and easy to setup
- a work environment for emergencies (computer breaking, computer gone)
- a reproducible environment (once no issues, no issues anywhere)
- a productive environment (some environments do too little to help and others too much)
```
sudo rm -rf /etc/nixos
sudo ln -s /home/$USER/<nix-config-folder> /etc/nixos
```

```
sudo nixos-rebuild switch --flake /etc/nixos
```
