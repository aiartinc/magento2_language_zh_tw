# Chinese (中文) Magento2 Language Pack (zh_TW)
## Magento 2 Traditional Chinese Language Pack

**Magento 2 Traditional Chinese Language Pack** is a helpful document that is donated by AI Art Inc.. The package will contain two steps (Download & Contribute and Install) to point out how you can apply Traditional Chinese Language on the storefront and backend of Magento 2 store. All phrases are contributed by Magento 2 translation project at Crowdin.



## Overview

- Download & Contribute
- Install Traditional Chinese Language Pack
- How to Install Traditional Chinese Language Pack

## 1. Download & Contribute to Traditional Chinese Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Traditional Chinese Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/HamiltonWang/magento2_language_zh_tw/archive/master.zip)
- [Download .tar.gz](https://github.com/HamiltonWang/magento2_language_zh_tw/tarball/master)


Find other [language packs here](https://www.mageplaza.com/kb/magento-2-language-pack/)

## 2. How to Install Traditional Chinese Language Pack

There are 3 different methods to install this language pack.

### ✓ Method #1. Composer method (Recommend)
Install the Traditional Chinese language pack via composer is never easier.

**Install Traditional Chinese pack**:

```
composer require aiart/magento2_language_zh_tw:dev-master
php bin/magento setup:static-content:deploy zh_TW
php bin/magento cache:flush

```


**Update  Traditional Chinese pack**:

```
composer update HamiltonWang/magento2_language_zh_tw:dev-master
php bin/magento setup:static-content:deploy zh_TW
php bin/magento cache:flush

```


### ✓ Method #2. Copy & Paste method (Not recommended)

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Traditional Chinese language pack
- Step 2: Unzip Traditional Chinese pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Traditional Chinese language pack

You can download the language pack from above link

#### Step 2: Unzip Traditional Chinese pack

Unzip the Traditional Chinese language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip app/code/aiart/zh_tw
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

```
php ./bin/magento cache:clean
php ./bin/magento cache:flush
```

### ✓ Method #3. Download and install manually (Not recommended)

To download and install Traditional Chinese pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/HamiltonWang/magento2_language_zh_tw/archive/master.zip)
- [Download .tar.gz](https://github.com/HamiltonWang/magento2_language_zh_tw/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `zh_TW.zip` into `app/i18n/aiart/zh_TW/zh_TW.csv`

#### Step 2: Flush cache

```
php ./bin/magento cache:clean
php ./bin/magento cache:flush
```

## 3. How to activate Traditional Chinese language pack

Now time to active the Traditional Chinese language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Traditional Chinese language pack}}](https://cdn.mageplaza.com/media/general/aPSUA0l.png)


## 4. How to contribute
<!-- ![process](http://progressed.io/bar/10) -->

Contribute to this language at https://crowdin.com/project/magento-2/zh-TW

## 5. Supported Magento versions

- Magento v2.0.x
- Magento v2.1.x
- Magento v2.2.x



## Note

- This project automatically updates weekly from Crowdin.
- Any question, issue please [create a new issue](https://github.com/HamiltonWang/magento2_language_zh_tw/issues/new)

## 6. Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [AI Art Inc. team](https://www.aiart.io/)


## 7. References:

- https://www.aiart.io/language_zh_tw.html
- https://crowdin.com/project/magento-2


## 8. Packagist
https://packagist.org/packages/aiart/magento2_language_zh_tw

