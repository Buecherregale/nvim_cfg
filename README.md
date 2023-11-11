# Neovim Config using NvChad
## Requirements
1. Neovim > 0.9.0
2. Nerd Font (JetbrainsMono Nerd Font)
3. [mingw32](https://github.com/Vuniverse0/mingwInstaller/releases/download/1.2.0/mingwInstaller.exe) on path
4. make: under Windows choco install make (GnuWin32) on path 
5. NvChad: git clone https://github.com/NvChad/NvChad %LOCALAPPDATA%\nvim --depth 1 && nvim <br>
    alternative paths:  <br>
        $HOME\AppData\Local\nvim <br> 
        %USERPROFILE%AppDataLocal\nvim <br>
        C:Users%USERNAME%AppDataLocal\nvim <br>

## Usage
This config sits in C:\Users\<username>\AppData\Local\nvim\lua

## Add Lsp
1. Add lsp to ensure installed in [plugins](./custom/plugins.lua)
2. Add lspgconfig.<lspname>.setup in ./custom/configs/lspconfig.lua

