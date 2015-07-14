## Sensu-Plugins-irc

[ ![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-irc.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-irc)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-irc.svg)](http://badge.fury.io/rb/sensu-plugins-irc)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-irc/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-irc)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-irc/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-irc)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-irc.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-irc)
[![Codeship Status for sensu-plugins/sensu-plugins-irc](https://codeship.com/projects/b54b1900-ea2d-0132-13b2-32dfa18a9fce/status?branch=master)](https://codeship.com/projects/83061)

## Functionality

## Files
 * bin/handler-irc.rb

## Usage
```
{
  "irc": {
    "irc_server": "irc://sensubot:password@irc.freenode.net:6667#channel",
    "irc_ssl": false
    // "nickserv_password": "bananas",
    // "nickserv_command": "PRIVMSG NickServ@some.special.hostname :IDENTIFY password"
  }
}
```
## Installation

[Installation and Setup](https://github.com/sensu-plugins/documentation/blob/master/user_docs/installation_instructions.md)

## Notes
