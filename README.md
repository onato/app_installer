This script will download the latest build of an app from the GitHub release assets, install it on a simulator, and launch it.

It relies on Xcode app archives being in the release assets with a certain naming convention. To see how to build and upload one, take a look at the [build script for TypeReader](https://github.com/onato/TypeReader/blob/main/scripts/build.sh).

# Dependencies
- Xcode
- [GitHub CLI](https://cli.github.com/)

# Setup
The first time you run, `~/.config/app_launcher.yaml` will be created. This is where you can define the GitHub repositories that have archives that you would like to be able to launch.

You can list the available apps.
```zsh
./app_installer --list-apps
``` 

# Help
```bash
./app_installer --help
```

# Demo
https://github.com/onato/app_installer/assets/107999/7e599037-2efd-4883-9658-3055bd705c35

