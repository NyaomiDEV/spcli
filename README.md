# spcli

## Prerequisites

This script requires `bash` and `jq` installed in your system. Please check if you have those dependencies installed before running `spcli`.

## Usage

- spcli help: Shows the help message.
- spcli id: Shows your user ID.
- spcli add \<memberID\>: Add someone to front.
- spcli remove \<memberID\>: Remove someone from front.
- spcli set \<memberID\>: Set someone as front.
- spcli status \<memberID\> \<customStatus\>: Update the custom status of a fronting member.
- spcli fronts: Show the current fronting members.
- spcli friends \<userID\>: Query the fronters on a friends' account.

## Configuration

Copy `spcli.conf` to `$XDG_CONFIG_HOME`. You have to have `$XDG_CONFIG_HOME` set up in your system!

Configure it to your likings. Most notably you'll need a SP token.

## License

The following software is licensed under MPL-2.0. Please check the LICENSE file.
