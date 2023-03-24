This solution will work if the “Use Categories Path for Product URLs” option is set to No from the Magento backend. 

install the module using the below commands.

#COPY CODE
Upload files to app/code

#Enable module 
php bin/magento module:enable Sharpeningservices_MailAttachment;

#Upgrade module 
php bin/magento setup:upgrade;

#Compile module 
php bin/magento setup:di:compile;

#Clear Cache
php bin/magento cache:clean;
php bin/magento cache:flush;

#Deploy static content
php bin/magento setup:static-content:deploy -f;

