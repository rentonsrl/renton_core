
# Magento Renton Core Extension

Requirement For Installation Extension:
Magento Version  ver.2.4.3 or higher,
Elasticsearch 7.7,
Php Version 7.4,
PHP, Elasticsearch Version and Other all requirement according to Magento Version.

Enable extension
php bin/magento module:enable Renton_Core
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
