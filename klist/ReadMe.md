# Sliver klist BOF

Below is a port of the @outflanknl klist BOF to Sliver. All kudos goes to them for the original code.

## Quick Start

The quickest way to add this to Sliver is as follows.

1. Download the zip file from the releases here: https://github.com/Cyb3rC3lt/SliveryArmory/releases/tag/v1.0.0
2. Extract it to a folder on your machine
3. Within Sliver load the folder you extracted with this command: `extensions install /home/david/klist`
4. Then load the extension into Sliver as follows: `extensions load /home/david/.sliver-client/extensions/klist`

## Install From Source

1. Make sure that Mingw-w64 (including mingw-w64-binutils) has been installed.
2. Download the source folder above.
3. Within that folder execute "make" to compile the object files.
4. Now you have the object files like they appear in the release zip folder

## Usage

To display all the cached Kerberos tickets

`klist`

To purge all the cached Kerberos tickets

`klist purge`

## Screenshots

![image](https://github.com/Cyb3rC3lt/SliveryArmory/assets/33097451/4ac8bf58-9134-4c1d-9d00-efe0bee11b75)

![image](https://github.com/Cyb3rC3lt/SliveryArmory/assets/33097451/146cafe6-f3c8-43c6-ad8c-2ad417bfd129)






