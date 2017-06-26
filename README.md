# Fikaba 
Fikaba is an imageboard engine forked from futallaby aiming to be more standards-compatible, readable, usable, and generally an updated version of futallaby, since futallaby has become abandonware.

[See here for info on migrating from futallaby](https://github.com/knarka/fikaba/blob/master/docs/migrate.md)

## Instances
Below are some examples of sites running Fikaba. If you are using fikaba and want to be added to the list, please make a pull request or otherwise contact me to add your site to the list below.

* ~~[Chanola](http://chanola.netau.net/board/)~~ RIP

## Features
* Valid HTML5
* Fairly advanced admin/moderator/janitor panel
* [JSON API](https://github.com/knarka/fikaba/blob/master/docs/api.md)
* Tripcodes, capcodes
* Highly configurable
* Post references
* Oekaki
* [...and more](https://github.com/knarka/fikaba/blob/master/docs/features.md)

## Installation
This guide assumes you have a webserver with PHP (5.6 at least) already installed. Fikaba has only been tested on Apache, but should work on any server.

1. Place the files from this repository in a folder on your webserver and set the permissions of that folder to 777
2. Edit/move config.example.php to config.php and edit it
3. If you want to use oekaki, execute `git submodule init; git submodule update`, first in the root folder, and then in js/ritare. This will pull in the oekaki applet and its dependencies, respectively.
4. Navigate to imgboard.php in your browser
5. Log in to the default admin account (password REPLACEME) and create a new account. The default one will be automatically removed
6. Pour yourself some puerh and admire your professional adminship

## Updating
[See here](https://github.com/knarka/fikaba/blob/master/docs/update.md)

## Contributing
Contributions are welcome. Github wants me to make a CONTRIBUTING file, but I won't.

## License
See the file LICENSE.
