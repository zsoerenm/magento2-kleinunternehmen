Zorn_Kleinunternehmen
===================

Sets german law rules regarding kleinunternehmen (Kleinunternehmerregelung)

Installation
------------

### Via composer

Please go to the Magento2 root directory and run the following commands in the shell:

```
composer config repositories.zorn_kleinunternehmen vcs git@github.com:zsoerenm/magento2-kleinunternehmen.git
composer require zsoerenm/magento2-kleinunternehmen
bin/magento module:enable Zorn_Kleinunternehmen
bin/magento setup:upgrade
```

Uninstall
------------

```
bin/magento module:uninstall Zorn_Kleinunternehmen
bin/magento setup:upgrade
```

Copyright
---------
(c) 2017 Sören Zorn
