# Template Dashkit

This is a template dashkit for HobDrive. It provides a simple, clean dashboard layout that you can use as a starting point for creating your own custom dashboards.

## Screenshots

*Add screenshots of your dashkit here*

## Features

- **Main Dashboard:** Large speed and RPM displays with essential vehicle info
- **Trip Computer:** Comprehensive trip statistics and fuel economy data
- **Info Screen:** Detailed vehicle sensors and environmental data
- **GPS Screen:** GPS data display (shown only when GPS is available)

## Included Screens

1. **Dashboard** - Primary driving screen with speed, RPM, and key gauges
2. **Trip Computer** - Odometer, trip distance, fuel consumption, and economy
3. **Info** - System voltages, temperatures, and engine parameters
4. **GPS** - GPS coordinates, speed, altitude, and bearing (conditional)

## Customization

Edit the `user.layout` file to customize this dashkit:

- Change sensor positions by modifying the grid structure
- Add or remove sensors by editing `<item>` elements
- Adjust sizes using the `size` attribute
- Add custom images in the `images/` folder
- Create additional sections for more screens

See the main README.md and LAYOUT_SPEC.md for detailed documentation.

## Installation

1. Copy the `community/template` folder to your HobDrive installation
2. Rename the folder to your desired dashkit name
3. Edit `info.json` with your dashkit information
4. Customize `user.layout` to your preference
5. Launch HobDrive and select your dashkit

## Author

Your Name

## Version

1.0.0
