# tirand module

## Description

A simple random integer generator for the Titanium SDK.

## Building the module

Execute the following command:

	./build.py

## Installing the tirand module

Copy ca.varju.tirand-iphone-0.1.zip to your Titanium project's root directory.  It will be unpacked automatically into the modules/iphone directory during your next build.

Add the following element to your project's tiapp.xml:

	<modules>
		<module version="0.1">ca.varju.tirand</module>
	</modules>


## Usage

	var tirand = require("ca.varju.tirand");
	var randomInt = tirand.random();

## Author

Alex Varju

## License

Copyright (c) 2011 Alex Varju
Apache License 2.0
