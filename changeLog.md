# Realese
v0.3.2

# Tested On
* TouchDesigner 099 2021.12380

# New Features
* custom reports now supported as a table DAT with two column - label and value

# Improvements
* added custom parameter for signals id - this is issued by Signals
* added custom parameter for signals name - this is issued by Signals

# Bug Fixes
* TOX now correctly communicates TouchDesigner version and build to Signals

# Compatibility Warnings
* **BACKWARDS COMPATABILITY WARNING**  
Release v0.3.2 is not compatible with the previous versions of sudoSignals! This build moves to a new Service style model to allow for greater flexibility for Signals. If you're currently using the direct connection from the TDSignals Client to the dashboard, wait to upgrade.