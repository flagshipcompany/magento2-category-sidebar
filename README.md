# Magento 2.0 Flagship Sidebar extension

This extension will add the ability to show category tree from the store root category in a sidebar.

## Installation with composer
* Include the repository: `composer require flagship/magento2-category-sidebar`
* Enable the extension: `php bin/magento --clear-static-content module:enable Flagship_Sidebar`
* Upgrade db scheme: `php bin/magento setup:upgrade`
* Clear cache

## Installation without composer
* Download zip file of this extension
* Place all the files of the extension in your Magento 2 installation in the folder `app/code/Flagship/Sidebar`
* Enable the extension: `php bin/magento --clear-static-content module:enable Flagship_Sidebar`
* Upgrade db scheme: `php bin/magento setup:upgrade`
* Clear cache

## Configuration
* Select the root category or current category option you want to use from the config page from the admin panel
* Select children depth level
* Categories will appear in col.left sidebar of the theme
