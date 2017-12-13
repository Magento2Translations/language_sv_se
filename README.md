# Swedish (svenska) Magento2 Language Pack (sv_SE)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The Swedish (svenska) translations used can be found [here](https://crowdin.com/project/magento-2/sv).
This translation is usefull for people living in the Sweden (Sverige).

For our other language packs look at the [Magento2Translations](http://magento2translations.github.io/) page.

# Version & progress
This translation is generated from the branch [Head](https://crowdin.com/project/magento-2/sv#/Head) at Crowdin and based on the Magento 2.2.0 sourcefiles.
There have been  4735 strings translated of the 8763 strings in the Magento source.

Translation progress:![Progress](http://progressed.io/bar/54)

# Installation
**Please select the git branch appropriate for your magento version from this repo.**
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_sv_se:dev-master
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_sv_se/archive/master.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/language_sv_se`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/sv_SE/sv_SE.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*Swedish (Sweden)*'

# Contribute
To help push the '*Swedish (svenska) Magento2 Language Pack (sv_SE)*' forward please goto [this](https://crowdin.com/project/magento-2/sv) crowdin page and translate the lines.

# Authors
The translations are done by the [official Magento2 translations project](https://crowdin.com/project/magento-2).

Code generation is sponsored by [Wijzijn.Guru](http://www.wijzijn.guru/).