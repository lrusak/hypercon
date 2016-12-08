# HyperCon - Hyperion Configuration tool
This is a forked release from the LibreELEC team. This version of HyperCon contains changes to allow HyperCon to work with the Hyperion version available in the LibreELEC add-ons repository.

__Changes include:__
 1. Additional SSH control options (restart/reload)
 2. Added AML grabber section to the hyperion.config.json
 3. Added webConfig section to hyperion.config.json
 4. Removed the ability to install/uninstall hyperion (hyperion is installed/uninstalled via Kodi's add-on system)
 5. Fixed layout of some panels
 6. General cleanup
 7. Use gradle to build the entire release jar.

### Issues
Please post issues in the LibreELEC forum under the HyperCon subforum.

### Building HyperCon
HyperCon is now built using gradle instead of ant.
To build HyperCon simply use the following command in the root directory.
```
gradle build
```
To clean the build use the clean command
```
gradle clean
```
### Disclaimer

The LibreELEC Team is not affiliated with the Hyperion Team. The Hyperion Team hold all rights to the HyperCon name and logo, and the Hyperion name and logo.

