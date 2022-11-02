This solution will work if the “Use Categories Path for Product URLs” option is set to No from the Magento backend. The Magento configuration path for this option is mentioned above.

Please enabled and install the module using the below commands.

#COPY CODE

#Enable module 
php bin/magento module:enable Maxmize_Omitcategorypath
php bin/magento setup:upgrade
php bin/magento setup:di:compile
