__*[NOTE]:*__ See [Instructions](Instructions.markdown) for these stub documentation files. 


# PLUGIN_NAME.*

|                      | &nbsp; 
| -------------------- | ---------------------------------------------------------------
| __Type__             | [TYPE](http://docs.coronalabs.com/api/type/Library.html)
| __Corona Store__     | [PLUGIN_NAME](http://store.coronalabs.com/plugin/PLUGIN_NAME)
| __Keywords__         | 
| __See also__         | 

## Overview

This [Corona](https://coronalabs.com/products/corona-sdk/) plugin enables you to...


## Syntax

	local PLUGIN_NAME = require "plugin.PLUGIN_NAME"

### Functions

#### [PLUGIN_NAME.FUNCTION1()](FUNCTION.markdown)

#### [PLUGIN_NAME.FUNCTION2()](FUNCTION.markdown)

#### [PLUGIN_NAME.FUNCTION3()](FUNCTION.markdown)


### Properties

#### [PLUGIN_NAME.PROPERTY1](PROPERTY.markdown)

#### [PLUGIN_NAME.PROPERTY2](PROPERTY.markdown)

#### [PLUGIN_NAME.PROPERTY3](PROPERTY.markdown)

## Project Configuration

### Corona Store Activation

In order to use this plugin, you must activate the plugin at the [Corona Store](http://store.coronalabs.com/plugin/PLUGIN_NAME).


### SDK

When you build using the Corona Simulator, the server automatically takes care of integrating the plugin into your project. 

All you need to do is add an entry into a `plugins` table of your `build.settings`. The following is an example of a minimal `build.settings` file:

``````
settings =
{
	plugins =
	{
		-- key is the name passed to Lua's 'require()'
		["plugin.PLUGIN_NAME"] =
		{
			-- required
			publisherId = "REVERSE_PUBLISHER_URL",
		},
	},		
}
``````

### Enterprise

If you have activated this plugin, you can download this plugin from the corresponding plugin page in the [Corona Store](http://store.coronalabs.com/plugin/PLUGIN_NAME).


## Resources

### Sample Code

You can access sample code [here](SAMPLE_CODE_URL).

### Support

More support is available from the PUBLISHER_NAME team:

* [E-mail](mailto://PUBLISHER_CONTACT@PUBLISHER_URL)
* [Forum](http://FORUM_URL)
* [Plugin Publisher](http://PUBLISHER_URL)


## Compatibility

| Platform                     | Supported
| ---------------------------- | ---------------------------- 
| iOS                          | No
| Android                      | No
| Android (GameStick)          | No
| Android (Kindle)             | No
| Android (NOOK)               | No
| Android (Ouya)               | No
| Mac App                      | No
| Win32 App                    | No
| Windows Phone 8              | No
| Corona Simulator (Mac)       | No
| Corona Simulator (Win)       | No

