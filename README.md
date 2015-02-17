## Sensu-Plugins-irc

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-irc.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-irc)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-irc.svg)](http://badge.fury.io/rb/sensu-plugins-irc)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-irc/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-irc)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-irc/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-irc)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-irc.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-irc)

## Functionality

## Files
 * bin/handler-irc

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

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-irc -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-irc`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-irc' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-irc' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
