#Magento2 Province Italiane

Questo modulo è un fork di https://github.com/vmasciotta/MagentoProvinceItaliane

A differenza dell'originale, vengono utilizzate le nuove Patch https://devdocs.magento.com/guides/v2.3/extension-dev-guide/declarative-schema/data-patches.html
ed è stata aggiunta la Sud Sardegna (SU)


##Installazione tramite composer:
 aggiungere la riga seguente al composer del proprio progetto:
 
```
composer require dnafactory/module-province-italiane
```
 
 eseguire quindi all'interno della root di magento i seguenti comandi:

```
$ ./bin/magento cache:disable
$ ./bin/magento module:enable Vmasciotta_ProvinceItaliane
$ ./bin/magento setup:upgrade
$ ./bin/magento cache:enable
```
