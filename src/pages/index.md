---
title: Intro To Azure App Services
pageTitle: To access the documentation for Azure App Service and Azure CLI, you can visit the following links:.
description: Azure App Service is a platform-as-a-service (PaaS) offering from Microsoft Azure that allows you to build, deploy, and scale web applications and APIs easily
---

To access the documentation for Azure App Service and Azure CLI, you can visit the following links: {% .lead %}

{% link-grid %}

{% link-grid-link title="Installation" icon="installation" href="/" description="Step-by-step guides to setting up your system and installing the library." /%}

{% link-grid-link title="Architecture guide" icon="presets" href="/" description="Azure CLI (Command-Line Interface) is a command-line tool provided by Microsoft for managing Azure resources." /%}

{% link-grid-link title="Plugins" icon="plugins" href="/" description="Extend the library with third-party plugins or write your own." /%}

{% link-grid-link title="API reference" icon="theming" href="/" description="Learn to easily customize and modify your app's visual design to fit your brand." /%}

{% /link-grid %}

Possimus saepe veritatis sint nobis et quam eos. Architecto consequatur odit perferendis fuga eveniet possimus rerum cumque. Ea deleniti voluptatum deserunt voluptatibus ut non iste.

---

## Intro To Azure App Services

Azure App Service is a platform-as-a-service (PaaS) offering from Microsoft Azure that allows you to build, deploy, and scale web applications and APIs easily. It provides a fully managed environment for your applications, abstracting away the underlying infrastructure so you can focus on your code.

Azure CLI (Command-Line Interface) is a command-line tool provided by Microsoft for managing Azure resources. It allows you to interact with Azure services and resources directly from the command line, whether you are using Windows, macOS, or Linux. Azure CLI provides a set of commands and scripts to create, manage, and monitor Azure resources using a simple and consistent syntax.

To access the documentation for Azure App Service and Azure CLI, you can visit the following links:

-   Azure App Service documentation:  [https://docs.microsoft.com/azure/app-service/](https://docs.microsoft.com/azure/app-service/)
    
    -   Here you will find comprehensive documentation on various aspects of Azure App Service, including how to create and configure web apps, manage app settings, use deployment slots, scale your applications, and more.
-   Azure CLI documentation:  [https://docs.microsoft.com/cli/azure/](https://docs.microsoft.com/cli/azure/)
    
    -   This documentation provides detailed information on how to use Azure CLI to manage your Azure resources. You will find instructions on installing Azure CLI, getting started guides, command references, and examples for different Azure services.

Both documentation resources are regularly updated and cover a wide range of topics to help you understand and utilize Azure App Service and Azure CLI effectively. Whether you are new to App Service or CLI, or have experience with them, the documentation will provide valuable guidance and insights for your Azure development and management tasks.

## Quick start

To get started with Azure CLI, follow these steps:

1.  Install Azure CLI:
    
    -   If you are using Windows, download and install Azure CLI from the Microsoft website.
    -   If you are using macOS, you can install Azure CLI using Homebrew by running the command  `brew install azure-cli`.
    -   If you are using Linux, consult the Azure CLI documentation for instructions specific to your distribution.
2.  Open a command prompt or terminal window.
    
3.  Sign in to Azure:
    
    -   Run the command  `az login`. This will open a browser and prompt you to sign in with your Azure account.
    -   After signing in, return to the command prompt or terminal window.
4.  Select an Azure subscription:
    
    -   If you have multiple Azure subscriptions, you can view the available subscriptions by running the command  `az account list`.
    -   To select a specific subscription to work with, use the command  `az account set -s <subscription_id>`  and replace  `<subscription_id>`  with the ID of the desired subscription.
5.  Explore Azure CLI commands:
    
    -   To view the available commands and command groups, run the command  `az`  or  `az -h`.
    -   To view help for a specific command or command group, run the command  `az <command_or_group> -h`. For example,  `az vm -h`  will display help for managing virtual machines.
6.  Start using Azure CLI:
    
    -   You can start interacting with Azure resources using Azure CLI commands. For example, you can create, manage, and delete resources like virtual machines, storage accounts, and databases.
    -   Refer to the Azure CLI documentation and command references for information on specific commands and scenarios. The documentation provides detailed examples and explanations.

Azure CLI is a powerful tool that enables you to manage various aspects of your Azure infrastructure and services from the command line. Take some time to explore its features and capabilities to make the most of your Azure management experience.

### Installing dependencies

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

Once you have Azure CLI installed, you can verify the installation by opening a new command prompt, terminal, or PowerShell window and running the command `az version`. This command will display the version of Azure CLI installed on your system.



{% callout type="warning" title="start using Azure CLI to!" %}
After successful installation, you can start using Azure CLI to manage your Azure resources by running various Azure CLI commands. Remember to sign in to your Azure account using az login before you can interact with your Azure subscription.

Refer to the official Azure CLI documentation for detailed instructions on installing Azure CLI on various distributions of Linux: [Install Azure CLI on Linux](https://docs.microsoft.com/cli/azure/install-azure-cli-linux).

{% /callout %}

### Configuring the library

Sit commodi iste iure molestias qui amet voluptatem sed quaerat. Nostrum aut pariatur. Sint ipsa praesentium dolor error cumque velit tenetur quaerat exercitationem. Consequatur et cum atque mollitia qui quia necessitatibus.

```js
// cache-advance.config.js
export default {
  strategy: 'predictive',
  engine: {
    cpus: 12,
    backups: ['./storage/cache.wtf'],
  },
}
```

Possimus saepe veritatis sint nobis et quam eos. Architecto consequatur odit perferendis fuga eveniet possimus rerum cumque. Ea deleniti voluptatum deserunt voluptatibus ut non iste. Provident nam asperiores vel laboriosam omnis ducimus enim nesciunt quaerat. Minus tempora cupiditate est quod.

{% callout title="You should know!" %}
This is what a disclaimer message looks like. You might want to include inline `code` in it. Or maybe you’ll want to include a [link](/) in it. I don’t think we should get too carried away with other scenarios like lists or tables — that would be silly.
{% /callout %}

---


### Adding middleware

Officia nobis tempora maiores id iusto magni reprehenderit velit. Quae dolores inventore molestiae perspiciatis aut. Quis sequi officia quasi rem officiis officiis. Nesciunt ut cupiditate. Sunt aliquid explicabo enim ipsa eum recusandae. Vitae sunt eligendi et non beatae minima aut.

Harum perferendis aut qui quibusdam tempore laboriosam voluptatum qui sed. Amet error amet totam exercitationem aut corporis accusantium dolorum. Perspiciatis aut animi et. Sed unde error ut aut rerum.

Ut quo libero aperiam mollitia est repudiandae quaerat corrupti explicabo. Voluptas accusantium sed et doloribus voluptatem fugiat a mollitia. Numquam est magnam dolorem asperiores fugiat. Soluta et fuga amet alias temporibus quasi velit. Laudantium voluptatum perspiciatis doloribus quasi facere. Eveniet deleniti veniam et quia veritatis minus veniam perspiciatis.

---

## Getting help

Consequuntur et aut quisquam et qui consequatur eligendi. Necessitatibus dolorem sit. Excepturi cumque quibusdam soluta ullam rerum voluptatibus. Porro illo sequi consequatur nisi numquam nisi autem. Ut necessitatibus aut. Veniam ipsa voluptatem sed.

### Submit an issue

Inventore et aut minus ut voluptatem nihil commodi doloribus consequatur. Facilis perferendis nihil sit aut aspernatur iure ut dolores et. Aspernatur odit dignissimos. Aut qui est sint sint.

Facere aliquam qui. Dolorem officia ipsam adipisci qui molestiae. Error voluptatem reprehenderit ex.

Consequatur enim quia maiores aperiam et ipsum dicta. Quam ut sit facere sit quae. Eligendi veritatis aut ut veritatis iste ut adipisci illo.

### Join the community

Praesentium facilis iste aliquid quo quia a excepturi. Fuga reprehenderit illo sequi voluptatem voluptatem omnis. Id quia consequatur rerum consectetur eligendi et omnis. Voluptates iusto labore possimus provident praesentium id vel harum quisquam. Voluptatem provident corrupti.

Eum et ut. Qui facilis est ipsa. Non facere quia sequi commodi autem. Dicta autem sit sequi omnis impedit. Eligendi amet dolorum magnam repudiandae in a.

Molestiae iusto ut exercitationem dolorem unde iusto tempora atque nihil. Voluptatem velit facere laboriosam nobis ea. Consequatur rerum velit ipsum ipsam. Et qui saepe consequatur minima laborum tempore voluptatum et. Quia eveniet eaque sequi consequatur nihil eos.
