This solution will work if the “Use Categories Path for Product URLs” option is set to No from the Magento backend. 

install the module using the below commands.

#COPY CODE
Upload files to app/code

#Enable module 
php bin/magento module:enable Maxmize_Omitcategorypath
php bin/magento setup:upgrade
php bin/magento setup:di:compile

