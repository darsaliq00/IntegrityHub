# IntegrityHub - MMRL Module Repository

IntegrityHub is an automated repository that curates and maintains Play Integrity and Android root modules for MMRL (Magisk Module Repository Loader).

## Features

- **Automated Updates**: GitHub Actions runs every 6 hours to sync modules from their original sources
- **No Manual Downloads**: Modules are automatically pulled from their original developers' GitHub releases
- **Attribution**: Full credit to original module developers is maintained
- **Open Source**: All code is open source and available for the community

## Supported Modules

- **PlayIntegrityFix** - Fix Play Integrity verdicts

More modules coming soon!

## How It Works

1. Each module has a `track.yaml` file that specifies its source repository
2. GitHub Actions automatically checks for new releases every 6 hours
3. When updates are found, `mmrl-util` downloads the modules and generates metadata
4. The repository is deployed to GitHub Pages for MMRL to access

## Adding to MMRL

Add this repository URL to MMRL:
```
https://darsaliq00.github.io/IntegrityHub/
```

## Contributing

To add new modules to this repository, please:

1. Open an issue with the module GitHub repository link
2. Ensure the module has proper release tags and update information
3. The module will be evaluated for compatibility and added if appropriate

## License

This repository is licensed under GPL-3.0. Individual modules retain their original licenses.

## Credits

- MMRL Team for the module manager
- Module developers for their excellent work
- mmrl-util for automated synchronization
