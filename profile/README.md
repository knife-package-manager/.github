# comrade-package-manager

**comrade** is a fast, flexible, and lightweight package manager written in Rust.

## Features

- **Logging**: Track all installation, update, and removal actions via the `rade log status` command.
- **Cross-Platform Support**: Supports multiple platforms, including specific architectures such as `x86_64-apple-silicon-darwin`.

## Installation

### Windows

Download the installer and follow the instructions to install rade 

[Installer (x86_64)](https://github.com/rade-package-manager/rade-installer/releases/download/0.1/ComradeInstaller.exe)

> [!WARNING]
> Also, please install git bash, and make (as these are used by rade)..

### Linux / macOS

1. Run the following commands in your terminal to download and install comrade:
   ```bash
   curl -sSfL https://github.com/rade-package-manager/rade-installer/releases/download/0.1/installer.sh -o install.sh
   chmod +x install.sh
   ./install.sh
   ```
This command installs the install.sh file and runs install.sh.
After installation, the install.sh file will be automatically deleted.
For more information, please visit [installer repositry](https://github.com/rade-package-manager/rade-installer/)


## Usage

After installation, you can start using comrade by entering commands in your terminal. To check the installation was successful, run:

```bash
rade --version
```

### Viewing Logs

To view the log of recent actions:
```bash
rade log status
```

## Contributing

We welcome contributions from the community! If you'd like to contribute:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Submit a pull request with a clear description of your changes.

For more details, please see [CONTRIBUTING.md](https://github.com/rade-package-manager/rade-package-manager/blob/stable/CONTRIBUTING.md).

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/rade-package-manager/rade-package-manager/blob/stable/LICENSE) file for more details.

