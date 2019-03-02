# Elatebrain MultiFlatRates for Magento 2



[![Latest Stable Version](https://poser.pugx.org/elatebrain/module-multiflatrates/v/stable)](https://packagist.org/packages/elatebrain/module-multiflatrates)
[![Total Downloads](https://poser.pugx.org/elatebrain/module-multiflatrates/downloads)](https://packagist.org/packages/elatebrain/module-multiflatrates)


## How to install & upgrade Elatebrain_MultiFlatRates


#### 1. Install via composer (recommended)

We recommend you to install Elatebrain_MultiFlatRates module via composer. It is easy to install, update and maintain.

Run the following command in Magento 2 root directory.

##### 1.1 Install

```
composer require elatebrain/module-multiflatrates
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

##### 1.2 Upgrade

```
composer update elatebrain/module-multiflatrates
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

Run setup:di:compile command if your store is in Production mode:

```
php bin/magento setup:di:compile
```

#### 2. Copy and paste

If you don't want to install this module via composer, you can use this way. 

- Download [the latest version here](https://github.com/elatebrain/module-multiflatrates/archive/master.zip) 
- Extract `master.zip` file to `app/code/Elatebrain/MultiFlatRates` ; You have to create a folder path `app/code/Elatebrain/MultiFlatRates` if not exist.
- Go to Magento root folder and run upgrade command line to install `Elatebrain_MultiFlatRates`:

```
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```
