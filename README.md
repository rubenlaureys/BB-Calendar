# BB-Calendar

The calendar module is one of the default modules of the MagicMirror. This module displays events from a public .ical calendar. It can combine multiple calendars.

Using the module

To use this module, add it to the modules array in the config/config.js file:

modules: [
	{
		module: "calendar",
    
		position: "top_left",	// This can be any of the regions. Best results in left or right regions.
    
		config: {
    
			// The config property is optional.
			// If no config is set, an example calendar is shown.
			// See 'Configuration options' for more information.
		}
	}
]
