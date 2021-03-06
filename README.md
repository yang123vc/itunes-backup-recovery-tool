# iTunes Backup Recovery Tool
This tool recovers all media like pictures, videos and recorded audio from an (yet) unencrypted iTunes backup.

Requirements: Node.js Runtime ^4.0

## Setup
```bash
cd /into/repositoryFolder
npm install
chmod +x ./itunes-backup-tool.js
```

## Check a backup folder:

```bash
./itunes-backup-tool.js check /Users/xyz/yourBackupFolder
```

This will give you informations about the backup itself (if Info.plist exists)
and will show you how much files of the supported types exist in the folder.

## Copy all media files

```bash
./itunes-backup-tool.js copy /Users/xyz/yourBackupFolder /Users/xyz/destinationFolder
```

The new files are written to the destination directory with UUID filenames.


## Further informations

The Tool is in active development. Use at own risk.
It recovers all media like pictures, videos and recorded audio.
Currently supported file types are:

* image/png
* image/jpeg
* image/jpg
* video/quicktime
* audio/m4a

The File types are recognized via magic number bytes.

## Future Features

* Support for decrypted backups
* Contacts recovery
* SMS recovery
* And more...

## Please donate if you like and want to support development !

Ethereum: **0x686123523ef2d0d21c5e295ada6b46424e0b8e2c**

