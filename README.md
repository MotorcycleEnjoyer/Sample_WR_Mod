# Sample_WR_Mod
This is a temporary sample mod to get people started in WR Modding

Prerequisites:
- WR Launcher
- VSCode
- Luau Language Server, by JohnnyMoganz

1.) Make a mod template in WR Launcher and enable:

- Official WR Experience Mod
- Enable Workspace

2.) Run your server once to make sure above worked. You should see "Created script state for wr-official" near the top.

2.) Copy `wr_official` from this repository into `Documents/Warsaw Revamped/Mods`

3.) In `Mods/wr_official/.vscode/settings.json`

Replace `YOUR_USER_HERE` with your windows username.

4.) Make sure Partitions is extracted. If not:

In `Documents/Warsaw Revamped/Package Cache`
Extract `partitions-0.1.zip`
Rename the extracted folder to `partitions`
