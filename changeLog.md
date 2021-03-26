# Realese
v0.2.1

# Tested On
* TouchDesigner 099 2021.11180

# New Features
*  added par for custom reports (not yet implemented)
*  added links and pulse pars for help and documentation pages

# Improvements
* signals ID displayed on TOX
* connected state to Daemon correctly displayed on TOX
* custom controls from TOX sent to daemon on startup

*  added page for advanced settings
*  added par for startup delay (currently read only)
*  house cleaning - moved old python and marked code as deprecated 

# Bug Fixes
* Reports now update with correct current performance information from TouchDesigner.
* TOX start up state now correctly handled for most operational conditions
*  build process resets all custom pars to defaults to ensure correct state for user on dropping into network

# Compatibility Warnings
* **BACKWARDS COMPATABILITY WARNING**  
Release v0.2.1 is not compatible with the previous versions of sudoSignals! This build moves to a new Daemon style model to allow for greater flexibility for Signals. If you're currently using the direct connection from the TDSignals Client to the dashboard, wait to upgrade.