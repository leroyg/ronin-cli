# Ronin CLI

* [Source](https://github.com/ronin-ruby/ronin-cli)
* [Issues](https://github.com/ronin-ruby/ronin-cli/issues)
* [Documentation](http://ronin-ruby.github.io/docs/ronin-cli/frames)
* [Mailing List](https://groups.google.com/group/ronin-ruby)
* [irc.freenode.net #ronin](http://ronin-ruby.github.com/irc/)

## Description

Ronin CLI provides the Command-Line Interface for Ronin.

## Features

* Supports markdown man pages.
* Allows defining custom sub-commands.

## Synopsis

Execute a sub-command:

    $ ronin subcommand --options ...

List available commands:

    $ ronin help

View the man page for a subcommand:

    $ ronin help subcommand

## Examples

## Requirements

* [parameters] ~> 0.4
* [ripl] ~> 0.3
* [ripl-multi_line] ~> 0.2
* [ripl-auto_indent] ~> 0.1
* [ripl-short_errors] ~> 0.1
* [ripl-color_result] ~> 0.3
* [ripl-shell_commands] ~> 0.1

## Install

    $ gem install ronin-cli

## License

Copyright (c) 2006-2014 Hal Brodigan (postmodern.mod3 at gmail.com)

Ronin CLI is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Ronin CLI is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with Ronin CLI.  If not, see <http://www.gnu.org/licenses/>.

[parameters]: https://github.com/postmodern/parameters#readme
[ripl]: https://github.com/cldwalker/ripl#readme
[ripl-multi_line]: https://github.com/janlelis/ripl-multi_line#readme
[ripl-auto_indent]: https://github.com/janlelis/ripl-auto_indent#readme
[ripl-short_errors]: https://rubygems.org/gems/ripl-short_errors
[ripl-color_result]: https://github.com/janlelis/ripl-color_result#readme
[ripl-shell_commands]: https://github.com/postmodern/ripl-shell_commands#readme
