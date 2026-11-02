# MoulaPlanner Desktop

Requires Windows x64 and .NET Framework 4.8. Extract the complete MPD ZIP, including Media, Catalog.json and Theme.json. Close MPD normally before replacing its files. Keep your data and sessions; they are not part of the ZIP.

At first launch select your World of Warcraft Interface/AddOns directory with Browse, or choose Configure Later. The local setting is available to everyone under Addons Path; Staff users find it next to GitHub. A changed path is saved and applied after restarting MPD so active writes never switch destination midway. MPT or MPL need not be installed to accept the folder.

Ordinary update checks read public GitHub Releases without a token. Download opens the official Release asset; verify its SHA-256 against manifest.json. Later closes the prompt. GitHub unavailability does not prevent normal MPD operation. The Download action does not install or replace the running EXE.

Upload Patch and Upload All additionally require current canonical Staff access, an explicitly approved publisher account, a validated release inventory and GitHub repository Contents write access. Publisher authentication is separate from Discord and from any ChatGPT connection. Credentials are never bundled. Publisher setup requires a separate explicit approval; GitHub CLI is a separate prerequisite for publishers only.
