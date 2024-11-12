<p align="center">
  <img src="/img/nixvim.png" width="400" />
</p>

<h1 align="center">NixVim Config</h1>
<p align="center">NeoVim with the reproducibility of NixOS and the configurability of Vim</p>
<p align"center">This config is just at the beginning. I will add mor features soon.</p> 

## Imports

To integrate this module to your config just put the file in a Folder within your NixOS config-path and import it in the `configuration.nix`.

```nix
imports = [./modules/nixvim.nix]
```

## Config and Plugins

Plugin-List

- nvim-tree
- telescope
- lualine
- alpha
- web-devicons
- vim-css-color
- barbecue
- fugitive
- nix

## Contributing
Feel free to contribute if you think something is not perfect.

## Acknowledgements
 * [NixVim](https://github.com/nix-community/nixvim)
