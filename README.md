# FortiGate configuration to HTML format
Some sort of tools for analysing FortiGate firewall configuration and exporting to HTML format.

## Notes
* It will just process configuration files in text format.
* Tested only with FortiGate version 7.0.9
* Not Tested with vdom


## Features
* Explodes address, service and group objects.
* Finds duplicate address objects.
* Explodes firewal policies.
* Explodes IPSec phase-1/2 configurations.
* Creates single HTML file without any dependency.

## Requirements
* PHP >= 8.2.0

## Usage
Download FortiGate configuration from the device and run as follows;

	> php ./fgtohtml.php fortigate-config-file.conf

This creates a new version of the original file with .html extension.

### Trademarks
Products and Brands mentioned in this project are trademarks or registered trademarks of their respective holders.


### Highlight Backgroud Color
  Rules Be Highlight with any "all".
  Rules Be gray when disabled.

#### Enjoy!
