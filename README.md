# Roblox VSCode Icons

Going from scripting in Roblox Studio into scripting in VS Code may feel strange. Using [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons), the transition can be a bit smoother and things will feel much more familiar. Using `client`, `server`, and `shared` as folder names or `*.ts` file extensions (for roblox-ts) are supported.

Change your file and folder icons in VS Code to match the ones on Roblox Studio!

<img src=example.png style="max-height: 400px"/>

## Usage
1. Install the [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons) extension in VS Code.
1. When prompted after installation, choose `VSCode Icons` as the file icon theme.
1. [Download](https://github.com/charleskimbac/roblox-vscode-icons/releases) and open the `dark` or `light` theme folder, depending on which theme you'd like to use.
1. In a new file explorer, navigate to the following:  
    - Windows: `C:\Users\%username%\AppData\Roaming\Code\User` (or press `WinKey+R` and then enter that)  
    - Mac: `/Users/<your_user>/Library/Application Support/Code/User`
    - If you're having issues finding the folder, see [here](https://github.com/vscode-icons/vscode-icons/wiki/Custom).
1. Move/copy the `vsicons-custom-icons` folder (from the theme folder) into this `User` folder.
1. In VSCode, open the command palette (`Ctrl/Cmd+Shift+P`) and enter `user settings json`. The `settings.json` file should open.
1. Open the `vscode-settings.txt` file in the theme folder.
1. Copy and paste everything in the `vscode-settings.txt` file into a new line at the bottom of the `settings.json` file in VSCode.
    - Note that the last line already in `settings.json` should be `"workbench.iconTheme": "vscode-icons",`. If it is not there already, add it.
1. `Ctrl/Cmd+S` to save the file.
1. The changes should take effect immediately. If they don't, ensure your file icon theme is set to `VSCode Icons` in the command palette.

## Credits
All icons are owned by Roblox Corporation.
