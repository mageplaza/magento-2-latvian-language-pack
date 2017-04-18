## Magento 2 Latvian Language Pack

**Magento 2 Latvian Language Pack** will show you the simple way to interpret the default language into Latvian on the Magento 2 stores. The Latvian Language Package, the in-line translation guide, is the fastest way to translate mass localization files instead of having to locate the strings before. The data comes from translation project at Crowdin, then automatically all are delivered to the Latvian language. To install the language package on the store, please keep your eyes on this topic.

Read more [Magento 2 Latvian Language Pack](https://www.mageplaza.com/magento-2-latvian-language-pack.html)


## Overview

- Download & Contribute
- Install Latvian Language Pack
- How to Install Latvian Language Pack

## Download & Contribute to Latvian Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Latvian Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/mageplaza/magento-2-latvian-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-latvian-language-pack/tarball/master)
- [Copy & paste package](https://crowdin.com/project/magento-2/lv.zip)


Find other [language packs here]({https://www.mageplaza.com/kb/magento-2-language-pack/)

## How to Install Latvian Language Pack

There are 3 different methods to install this language pack.

### #1. Composer method
Install the Latvian language pack via composer is never easier.

**Install Latvian pack**:

```
composer require mageplaza/magento-2-latvian-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy lv_LV

```


**Update  Latvian pack**:

```
composer update mageplaza/magento-2-latvian-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy lv_LV

```

#### Authentication required (Optional)

[Authentication required](https://i.imgur.com/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)


### #2. Copy & Paste method

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Latvian language pack
- Step 2: Unzip Latvian pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Latvian language pack

You can download the language pack from above link

#### Step 2: Unzip Latvian pack

Unzip the Latvian language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip /var/www/html/
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### #3. Download and install manually

To download and install Latvian pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-latvian-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-latvian-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `lv_LV.zip` into `app/i18n/mageplaza/lv_LV/lv_LV.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## How to active language pack

Now time to active the language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Latvian language pack}}](https://i.imgur.com/aPSUA0l.png)


## Translation process of Latvian Language Pack
![process](http://progressed.io/bar/80)

Contribute to this language at https://crowdin.com/project/magento-2/lv

## Supported Magento versions

- Magento v2.0.0
- Magento v2.0.1
- Magento v2.0.2
- Magento v2.0.3
- Magento v2.0.4
- Magento v2.0.5
- Magento v2.0.6
- Magento v2.0.7
- Magento v2.0.8
- Magento v2.0.9
- Magento v2.0.10
- Magento v2.0.11
- Magento v2.0.12
- Magento v2.0.13
- Magento v2.1.0
- Magento v2.1.1
- Magento v2.1.2
- Magento v2.1.3
- Magento v2.1.4
- Magento v2.1.5
- Magento v2.1.6



## Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


References:
- https://www.mageplaza.com/magento-2-latvian-language-pack.html
- https://www.mageplaza.com/kb/magento-2-language-pack/