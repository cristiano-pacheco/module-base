# Cristiano Pacheco Magento 2 Base Module

## Installation

### With Composer

1-Add the session below to your composer.json file:

```
"repositories": [
    {
      "type": "vcs",
      "url": "https://github.com/cristianopacheco/module-base"
    }
  ],
```

```
composer require cristianopacheco/module-base
```

### With Modman

```
modman clone https://github.com/cristianopacheco/module-base
```

## To enable the module

```
bin/magento module:enable CristianoPacheco_ModuleBase
bin/magento setup:upgrade
```
