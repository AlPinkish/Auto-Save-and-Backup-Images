# Auto Save and Backup Images Addon for Blender

Automatically save modified images and create backups to prevent data loss.

![Addon Preview](https://github.com/user-attachments/assets/68654ce9-f116-4bab-a011-f2807270767d)

The Auto Save and Backup Images addon ensures that no progress is lost by automatically saving modified (dirty) images and creating backups in a specified directory. This can be done either automatically or when saving `.blend` files, providing a safeguard against crashes.

**I don’t know why this feature isn’t included by default in Blender!🤯**

## Features

- Auto-save images when saving .blend files
- Periodic image backups
- Excludes internal Blender images
- Customizable backup directory
- Optional debug output

## Installation

1. Download the addon from [GitHub Releases](https://github.com/AlPinkish/Auto-Save-and-Backup-Images/releases)
2. In Blender, go to Edit > Preferences > Add-ons
3. Click "Install" and select the downloaded .zip file
4. Enable the addon

## Usage

### Manual Save

Enable/disable in addon preferences: "AutoSave Images on Manual Save"

### Automatic Backups

1. Enable "Enable AutoBackUp" in preferences
2. Set "AutoBackUp Interval" (default: 30 seconds)

### Backup Directory

Set custom directory in "Backup Directory" field

### Debugging

Enable "Enable Debug Output in System Console" to check if the addon is working properly

## Troubleshooting

### Images not backing up? Follow these obvious tips
- Ensure you have enabled Enable AutoBackUp in the preferences. 
- Make sure the images have been modified (i.e., are marked as "dirty").
- The addon skips saving or backing up images that have not been modified.






### Backup directory not found?
- Verify that the specified backup directory exists and is accessible by Blender. The addon will attempt to create it if it doesn't exist.
  
## License

GNU General Public License (GPL) v3.0

## Contributing

Submit issues or pull requests on GitHub

## Support

- [PayPal](https://www.paypal.com/paypalme/alvarorosati)
- [Gumroad](https://alvarobot.gumroad.com/l/imagefinderforblender)
- [Alvaro Rosati Website](https://sites.google.com/view/alvaro-rosati/home-page?authuser=0)
