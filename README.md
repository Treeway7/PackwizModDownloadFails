# Packwiz Mod Download Fails - Bug Reproduction

This is an issue that pertains to the Packwiz Installer. The error occurs while running the pre-launch bootstrap.

For some reason, Packwiz does not download [BlossomEnderChest](https://modrinth.com/mod/blossomenderchest/)
and its dependency [BlossomLib](https://modrinth.com/mod/blossomlib), but it does still download other mods
(in this case, [ModernFix](https://modrinth.com/mod/modernfix/) and [Mod Menu](https://modrinth.com/mod/modmenu/)).

[Other Blossom series mods](https://modrinth.com/user/CodedSakura) are not affected.

To run this bug reproduction modpack:

1. Download the Auto-Updating instance from [this repository's releases](https://github.com/Treeway7/PackwizModDownloadFails/releases/).
2. Import it in [Prism Launcher](https://prismlauncher.org/).
3. Run the instance.
4. When the loader update prompt appears, click "Continue Anyways".
5. Check the console - it will say BlossomEnderChest and BlossomLib is checked and downloaded..?
6. The mods aren't even in the mods folder... How peculiar! However, ModernFix and Mod Menu did indeed download properly.
