# BF4DB-Modded Plugin

## Changelog
ward








## INSTALLATION 

There are a few steps to complete before this plugin will be operational. You must first have created an account with us and then claim a server. Once you have a server claimed you will be given an API key. Once you have placed the plugin in your Procon layer, the last step is to setup the plugin with the API key and change any settings you might need. Each of these steps will be outlined below.

**CLAIMING SERVER**
To claim a server please login and click Server Tools under the user menu. On the Server Tools page you can claim new servers and manage existing ones. You will then see a box that contains a unique code each time this page is visited and an input for your server Battlelog GUID. You must have admin access to your servers in order to claim them. The next step is to use whatever tool you use to manage your server to include the unique code in your server name. This is just temporary and can be changed once you have claimed the server. You do not need to change the entire server name to just the unique code, it only has to be in it somewhere. Once the name has been changed with the correct code, then place your server Battlelog GUID in the field and press Claim. If everything was correct you will have successfully claimed a server. Repeat this process for any or all servers you need to setup the plugin for! 

**GET API KEY**
Once you have a server claimed you will be given an API key to be used with our plugin. To get this key visit your Servers page under Settings and click on the API Key button next to the server. A box will pop-up with your API key. This key will never expire and can always be accessed here as long as you have the server claimed. This key will only work for the server it was claimed with. Copy the API key for the next step.

BF4DB reserves the right to revoke any API key generated for any server at any time. If a server is deemed to be a "hacked" server, or is openly harboring hackers (abusing the whitelist function), then it's API key will be revoked and account owners will be unavailable to claim additional servers in the future. 

**SETUP PLUGIN**
You must already have a Procon layer setup and running either hosted remotely or locally. Download the plugin using the links below. It will come in a .zip file and contain two files within. Unzip this and place both the included files in the Plugins\BF4 folder on your Procon layer filesystem. Please refer to the Procon manual or your layer provided for file access. After the files are in place restart your layer. 

**CONFIGURATION**
You will then need to open Procon to enable and configure the plugin. Before enabling please input the given API key and change any settings you may want. When the correct API key for that server is included you may then enable the plugin.

**SETTINGS**
API Key -
You must claim the server on BF4DB.com to receive an API key for this server.
Enable Auto Bans -
When set to Yes, any players banned on BF4DB will be removed from your server. Defaults to Yes.
Enable Announcements -
When set to Yes, player status during verification will be announced in chat. Defaults to Yes.
Player Whitelist -
Place any player names(one per line) to be excluded from BF4DB checks and server removal.
Debug Level -
Mainly for BF4DB developers. If you encounter an issue please set to one of the following levels before submitting a bug report:
0: Disabled. Not debugging in the console will occur.
1: Only player information will be logged.
2: Player and server information will be logged.
3: Player, server, and PunkBuster information will be logged. 

**DEVELOPMENT**
For any support or bug reports please visit our forums or use  support-tickets. Please included as much information or debugging as you can. 
NOTES
If your Procon layer host does not allow uploads of .dll files:

1) Rename BF4DB_API.dll to BF4DB_API.cs, then open BF4DB.cs and edit lines 103 and 105 from BF4DB_API.dll to BF4DB_API.cs, save, then proceed to upload the plugin. If you're not sure which line to edit (if your editor doesn't show line numbers), simply search (Ctrl+F) for .dll and change it to .cs. After you upload the plugin, you will need to reboot your Procon layer.

The above fix only applies to plugin version 2.0.14 and lower. 
LICENSE
BF4DB Server Protection by skuIIs is licensed under a Creative Commons Attribution-NoDerivatives 4.0 International License.
Permissions beyond the scope of this license may be available at https://bf4db.com/tos
