# Doc Templates for Library Plugins

## Overview

If you wish to distribute your plugin via the [Corona Store](http://store.coronalabs.com), you will be required to provide a URL for your documentation before your plugin is approved.

These template files will help you write documentation for library plugins.


## Hosting

To simplify the hosting of your plugin documentation, we have designed these template files to be hosted as a public github repository. 

As a starting point, we recommend you copy, clone or fork this repository.


## Files

This template provides the stub markdown files:

* [Readme.markdown](Readme.markdown)
	+ This is the main library index page.
	+ You should list all functions and properties here.
* [FUNCTION.markdown](FUNCTION.markdown)
	+ This is a template for all library functions.
	+ You should duplicate this file for each function in the library.
* [PROPERTY.markdown](PROPERTY.markdown)
	+ This is a template for all library properties (e.g. version information)
	+ You should duplicate this file for each property in the library.

NOTE: The files in ALL CAPS are stub files. The actual names of the files should match the case of the corresponding function/property names.


## Markdown Guidelines

The template files are based on markdown. 

Please consult [Github Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/) for guidelines for more information.

### Conventions

In the template files, there are various words that are written in all-caps. We recommend that you do a *bulk* find/replace before you start the actual documentation writing process. This will ensure your docs are consistent.

Some examples of bulk find/replace are shown below for a fictitious 'binaryjson' plugin developed by the fictitious 'MyCompany' developer:

* `PLUGIN_NAME` => `binaryjson`
* `FUNCTION` => `encode()`
* `PROPERTY` => `version`
* `TYPE` => `[String](http://docs.coronalabs.com/api/type/String.html)`
* `PUBLISHER_CONTACT` => `support@mycompany.com`
* `PUBLISHER_NAME` => `MyCompany`
* `PUBLISHER_URL` => `http://mycompany.com/`
* `FORUM_URL` => `http://mycompany.com/forums/binaryjson`
* `REVERSE_PUBLISHER_URL` => `com.mycompany`
* `SAMPLE_CODE_URL` => `http://github.com/mycompany/binaryjson-sample`


