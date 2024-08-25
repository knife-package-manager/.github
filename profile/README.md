**comrade** is a package manager designed to build programs from source code using `make`, ensuring that each program is optimized for the user's specific environment. Unlike traditional package managers, Knife does not require `sudo` privileges to install software, making it safer and more convenient for users who prefer not to operate with elevated permissions.

**Key Features:**
- **Source-based Installation:** comrade compiles programs directly from source, allowing for custom optimizations tailored to your system's architecture.
- **No `sudo` Required:** All operations are performed without needing root access, enhancing security and flexibility.
- **Easy to Use:** The command `rade install <program>` simplifies the installation process. comrade also offers commands like `rade update` to keep the package manager itself up-to-date and `rade upgrade` to upgrade installed programs.
- **Rust Implementation:** Written in Rust, comrade is both fast and safe, leveraging Rust's performance and memory safety features.
- **Universal Compatibility:** comrade is designed to work in any environment, ensuring broad usability across different systems.

**Installation:**
To install comrade, use the following command:
```
curl -sSfL https://github.com/rade-package-manager/rade-installer/releases/download/0.1/installer.sh -o install.sh; chmod +x install.sh; ./install.sh 
```
