# Aiken Installation Instructions

## Via Aikup
First, install **Aikup**, a basic cross-platform utility tool to download and manage Aiken's versions and ensure seamless upgrades. Once installed, simply run:


Install Aikup :

## NPM
```bash
npm install -g @aiken-lang/aikup
```

## HomeBrew
```bash
brew install aiken-lang/tap/aikup
```

## From url (Linux & MacOS)
```bash
curl --proto '=https' --tlsv1.2 -LsSf https://install.aiken-lang.org | sh
```

# From url Windows
```bash
powershell -c "irm https://windows.aiken-lang.org | iex"
```

# Language Server

The `aiken` command-line tool comes with a built-in Language Server. If needed, configure your language client with the following settings (refer to your language client’s documentation for specific instructions):

- **Command**: `aiken lsp` (note: this command may not be visible in the command-line help)
- **Root Pattern**: `aiken.toml`
- **Filetype**: `aiken` (`.ak`)

The Language Server supports a variety of capabilities (though not all). For more details, please refer to the [supported capabilities](https://github.com/aiken-lang/aiken/blob/main/README.md#language-server) in the main repository.

## Sample Project File Tree

```bash
my-aiken-project/
├── README.md            # Project documentation
├── aiken.toml           # Project configuration file
├── lib                  # Directory for library modules
│   └── bar              # Subdirectory for specific library functions
└── validators           # Directory for smart contract validators
```

To help you get started, here's a sample file tree structure for an Aiken project:



