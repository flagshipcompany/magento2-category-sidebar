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
* Enable the module from the config page from the admin panel
* By default, the category tree will be visible on the front end for each category.
* To display the category tree on the Home Page, from the admin panel, Content > Pages > Home Page > Design. Change Layout to 2-columns with left bar
* Effect layout changes: `php bin/magento setup:upgrade`
* Categories will appear in col.left sidebar of the theme
