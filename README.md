# Pantheon Updates
A bash shell script to check for Pantheon site updates.

## Prerequisites:
- Terminus: See https://pantheon.io/docs/terminus/install.
- Terminus Composer Plugin: See https://github.com/pantheon-systems/terminus-composer-plugin.
_Note: The Terminus Composer Plugin is only needed for Composer managed sites._

## Installation:
```bash
$ git clone https://github.com/uberhacker/pantheon-updates.git
$ cd pantheon-updates
$ sudo cp pantheon-updates /usr/local/bin
```

## Usage:
```bash
$ pantheon-updates
```
This will loop over all the available Pantheon sites and report on core and module/plugin updates for Drupal and WordPress.  You will need to login with a machine token if this is the first time using Terminus.  See https://pantheon.io/docs/terminus/install#machine-token.
