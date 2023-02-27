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

## #3

```txt
.
├── settings: contains various settings files, such as options.lua for configuring Neovim options and theme.lua for setting up the color scheme.
├── plugins: contains configuration files for various plugins, each in their own subdirectory. For example, plugins/nvim-tree.lua for configuring the NvimTree plugin and plugins/lspconfig.lua for configuring the LSP server.
├── mappings: contains mapping configuration files, such as keymappings.lua and pluginmappings.lua.
├── utils: contains utility functions that can be used throughout the configuration, such as helpers.lua for commonly used functions or autocmds.lua for defining autocommands.
└── modules: contains various Lua modules that can be used throughout the configuration, such as statusline.lua for defining a custom statusline or completion.lua for defining custom completion functions.
```
