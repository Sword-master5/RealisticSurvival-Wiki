# Configuring Realistic Survival
This part assumes you now have Realistic Survival installed on your server.

When viewing the Realistic Survival plugin folder, you will notice a few different .YML files. Start by viewing *config.yml* in your favorite text editor.
Personally, I recommend [Notepad++](https://notepad-plus-plus.org).

Most of the things in this file are very self explanatory, from enabling certain modules to customizing
various messages.

**Items.yml*** allows you to enable or disable certain items *globally*. If you install multiple addons for Realistic Survival, this file can get very big,
so, a recommendation is to take your time and install addons slowly, if again, you plan on enabling or disabling certain items.

**messages.yml** contains all data for messages when using Realistic Survival. You can edit what the plugin sends a player when a certain event occurs.

**Researches.yml** allows you to edit the XP Values of items in Realistic Survival, as well as their names, you can also disable researching all together if you wish to allow players
the ability to use all of Realistic Survival right off the bat.

**permissions.yml** allows you to define permission nodes for Realistic Survival items to restrict the usage of items based on user's permission levels.

Any changes you make should be saved, then restart the server. Again, ***do not use /reload.*** If you are experiencing issues, and you issued a server reload,
just stop and restart the server, since this fixes most issues.
