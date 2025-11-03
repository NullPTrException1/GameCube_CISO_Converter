# GameCube_CISO_Converter
A Conversion script for GameCube .ciso files. Bundles [Wiimms ISO Tools](https://github.com/Wiimm/wiimms-iso-tools) and [NKit](https://github.com/Nanook/NKit) to create a functional GameCube ISO.

## Available Builds
- Windows, Linux, MacOS

## Requirements (Linux)
You must have mono installed for the NKit step to run successfully. You can install this as follows:
1. If you are on a distro that is not Arch-based, follow these instructions: https://www.mono-project.com/download/stable/#download-lin
2. If you are on an Arch Linux distro, you can get mono from package manager: `sudo pacman -S mono`

## Requirements (MacOS)
You must have mono installed for the NKit step to run successfully. You can install this from here: https://www.mono-project.com/download/stable/#download-mac

## Usage (Windows)
1. Put your GameCube .ciso file in the CISO folder.
2. Run ConvertCISO.bat.
3. Once it finishes, your ISO will be in NKit/Processed/Gamecube.

## Usage (Linux)
1. Put your GameCube .ciso file in the CISO folder.
2. Open a terminal in the GC_CISO_Converter folder.
3. Make the sh file executable: `chmod +x ConvertCISO.sh`
4. `./ConvertCISO.sh`
5. Once it finishes, your ISO will be in NKit/Processed/Gamecube.

### NOTE: This can only handle one .ciso at a time in the CISO folder. Will look into batch conversion in later builds.

If you run into any issues ping @nullptr33 on Discord.
