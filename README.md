```
sudo rm -rf /etc/nixos
sudo ln -s /home/$USER/<nix-config-folder> /etc/nixos
```

```
sudo nixos-rebuild switch --flake /etc/nixos
```
