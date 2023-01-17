### Commands


sudo nixos-rebuild switch -I nixos-config=/home/dm/.dotfiles/configuration.nix

1. add git to packages in /etc/nixos/configuration.nix
2. sudo nixos-rebuild switch
3. git clone this repo
4. remove git from packages in /etc/nixos/configuraiton.nix
5. sudo nixos-rebuild switch
6. add git to ~/.dotfiles/configuration.nix
7. add neovim overlay to flake.nix
8. sudo nixos-rebuild switch --flake /home/dm.dotfiles
