---
title: Install Azure CLI
description: To install Azure CLI, follow the instructions below based on your operating system
---

To install Azure CLI, follow the instructions below based on your operating system:

**Windows:**

1. Download the MSI installer for Azure CLI from the Microsoft Download Center: [Azure CLI for Windows](https://aka.ms/installazurecliwindows).
2. Once the download is complete, run the installer file (.msi) to start the installation.
3. Follow the prompts in the installer, review and accept the license terms, and choose the installation location if desired.
4. Click "Install" to begin the installation process.
5. After the installation is complete, open a new command prompt or PowerShell window and run the command `az login` to sign in to your Azure account.

**macOS:**

1. Open a terminal window.
2. Run the following command to install Azure CLI using Homebrew:

```shell
brew update && brew install azure-cli
```

3. If you don't have Homebrew installed, you can install it by running the following command:

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

4. After the installation is complete, run the command `az login` to sign in to your Azure account.

**Linux:**

- Refer to the official Azure CLI documentation for detailed instructions on installing Azure CLI on various distributions of Linux: [Install Azure CLI on Linux](https://docs.microsoft.com/cli/azure/install-azure-cli-linux).

Once you have Azure CLI installed, you can verify the installation by opening a new command prompt, terminal, or PowerShell window and running the command `az version`. This command will display the version of Azure CLI installed on your system.

After successful installation, you can start using Azure CLI to manage your Azure resources by running various Azure CLI commands. Remember to sign in to your Azure account using `az login` before you can interact with your Azure subscription.


