# neovim-lua-folder-structure-collection

[tree generator](https://tree.nathanfriend.io/)

> Contributions are welcome.

## #1

```txt
lua/
├── lsp/                # LSP-related configuration
├── plugins/            # Plugins-related configuration
├── settings/           # General Neovim settings
├── mappings/           # Key mappings
├── utils/              # Utility functions and modules
└── init.lua            # Entry point for sourcing all configuration files
```

## #2

```txt
lua/
├── keybindings/ # Folder for organizing keybinding configurations.
├── plugins/ # Folder for managing plugins and their configurations.
├── completion/ # Folder for configuring completion engines and related settings.
├── lsp/ # Folder for LSP (Language Server Protocol) configurations and settings.
├── themes/ # Folder for managing and configuring themes and color schemes.
├── utils/ # Folder for utility functions and modules that can be used throughout your configuration.
├── ui/ # Folder for configuring UI elements and appearance settings.
└── settings/ # Folder for general settings that don't fit into any of the other categories.
```
