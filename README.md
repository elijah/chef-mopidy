# chef-mopidy
[![Build Status](https://travis-ci.org/elijah/chef-mopid.svg?branch=master)](https://travis-ci.org/elijah/chef-mopidy)

## Description

Installs and configures a copy of Mopidy media server.

* Source Code: http://github.com/elijah/chef-mopidy

## Requirements

### Chef

Tested on chef 12

### Cookbooks

* [build-essential](http://community.opscode.com/cookbooks/build-essential)
* [python](http://community.opscode.com/cookbooks/python)
* [apt](http://community.opscode.com/cookbooks/apt)

### Platforms

* Ubuntu 14.04+
* CentOS 7.0+

## Recipes

### default

The default recipe installs eveything you need.

### _debian

This recipe should install the proper package dependencies for Ubuntu and Debian hosts.

### centos

This recipe should install the proper package dependencies for RedHat and CentOS style hosts.

## Attributes

### Default

* `minecraft['banned-players']`
  - An array of players you would like banned, default blank


### Properties


### Known issues


## Contributing

1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Added some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request

## License

Author: Elijah Wright <elijah.wright@gmail.com>

With kudos to github.com/paulsturgess/mopidy-vagrant , which I used as a starting point for this work. 

Copyright 2016.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
