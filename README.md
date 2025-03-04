# Brother DCP-T420W Printer Driver for Arch Linux

This repository contains a patched version of the Brother DCP-T420W printer driver for Arch Linux.

## 📥 Installation
1. Download the `.zst` package.
2. Open a terminal and navigate to the directory containing the downloaded file.
3. Run the following command to install the package:
   ```sh
   sudo pacman -U dcpt420wpdrv-3.5.0-1-x86_64.pkg.tar.zst
   ```
4. Install and Enable and start CUPS if not already running:
   ```sh
   sudo pacman -S cups && sudo systemctl enable --now cups
   ```
## 🎉 Done!
Your Brother DCP-T420W printer should now be working on Arch Linux.


## NOTE! 
- Cups Service should be running.
- Some times it gives errors about the lp group you can manually create it and then create the directories it complaints about.

