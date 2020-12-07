# Compiling from source code

## Building zip installers of plugins

* acquire the source code
* ensure [Composer](https://getcomposer.org) is installed
* from the source code directory, run `composer install`
* from same directory, run `composer build ZIP_NAME`, where _ZIP_NAME_ is a friendly name, such as `wp2static-addon-s3`.

If all goes well, this will put a zip file for easy installation of the plugin into your `$HOME/Downloads` directory. You can now install this to your WordPress site via the dashboard’s _Plugins > Add Plugins > Upload Plugin_ area.
