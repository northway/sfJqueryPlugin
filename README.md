# sfJqueryPlugin For Symfony 1.4

Contains:
 - jQuery 1.11.2 compressed

##  Git

Git submodule add:

	$ git submodule add https://github.com/northway/sfJqueryPlugin.git plugins/sfJqueryPlugin

Git submodule update:

	$ git submodule update --remote

## Install

You need to add this line to ProjectConfiguration.class.php:

    $this->enablePlugins('sfJqueryPlugin');

Then a Symfony cache clear:

		$ php symfony cc

## Usage

view.yml:

  default:
    javascripts:
      - /sfJqueryPlugin/js/jquery-1.11.2.min.js

If you run into some error, check symfony logs and script logs.

If you think you can improve this plugin or found some error, feel free to fork and create a pull request.