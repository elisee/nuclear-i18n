nuclear-i18n
============

i18next wrapper with markdown support for Express applications.


## Install

    $ npm install nuclear-i18n

## Usage

Pass your Express app object to the module just before setting up your router middleware.

    require('./lib/i18n')(app)

The module will look for the locale files in `public/locales/%{lng}/%{ns}.json`.
You can optionally pass a list of locale namespaces as a second argument.
