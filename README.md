____________
## **Forked:** Added support for Modrinth modpacks
*container information can be found [here](https://github.com/itzg/docker-minecraft-server/blob/master/README.md#running-a-server-with-a-modrinth-modpack)*
____________
<br>

# Azure Minecraft Server

A simple ARM template to quickly setup a minecraft server on azure

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FGeoDerp%2Fazure-minecraft-server%2Fmodrinth%2Ftemplates%2Fitzg-minecraft-server.json)

## What does it create

- One storage account with a file share to store the server files
- One azure container instance with the [itzg/minecraft-server](https://hub.docker.com/r/itzg/minecraft-server) image

## How to use

1. Click the "Deploy to Azure" button.
2. Sign in with your Azure account.
3. Select your subscription and resource group to deploy, the resources will be created on the resource group's region. If you're creating a new resource group, you'll have to select a region, select the region closest to your location.
4. Click Review + Create, then Create. Your server will be created shortly.

## Roadmap

- [x] OP (Administrators) support
- [ ] All environment variables support
- [ ] Friendly user interface to select version, cpu/memory and administrators

## Contributing

Feel free to open a pull request adding whatever feature you'd like to see here, I'll be glad to review it!

If you feel like donating, I'd be forever thankful!

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=ZZYJ94ADD9VLW&currency_code=BRL&source=url)
