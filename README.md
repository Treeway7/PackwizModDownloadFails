# Packwiz Mod Install Fails - Bug Reproduction

For some reason, Packwiz does not download [BlossomEnderChests](https://modrinth.com/mod/blossomenderchest/)
and its dependency [BlossomLib](https://modrinth.com/mod/blossomlib), but it does still download other mods
(in this case, [ModernFix](https://modrinth.com/mod/modernfix/) and [Mod Menu](https://modrinth.com/mod/modmenu/)).

[Other Blossom series mods](https://modrinth.com/user/CodedSakura) are not affected.

To run this bug reproduction modpack:

1. Download and import the Auto Updating instance from the Releases in [Prism Launcher](https://prismlauncher.org/)
2. Run the instance
3. Check the console - it will say BlossomEnderChest is checked and downloaded
4. The mods aren't even in the mods folder... How peculiar! However, ModernFix and Mod Menu did indeed download properly.
