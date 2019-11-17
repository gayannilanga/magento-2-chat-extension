# Chat Module - Aligent Code Challenge
This is a sample Magento 2 module done to achieve the the coding challenge given by Aligent Consulting.

# Background
This module developed and tested on Magento Commerce version 2.3.2 

# System Requirements
Linux OS (Ubuntu / CentOS)  
Apache 2.4 or higher  
PHP 7  
Vanila Magento 2.3.2 commerce installation  
composer tools  

# How to install this extension?
Under your root folder, run following commands  
    - composer require aligentweb/magento-2-chat-extension   
    - php bin/magento module:status (optional)  
    - php bin/magento module:enable Aligentweb_Chat  
    - php bin/magento setup:upgrade  
    - php bin/magento setup:static-content:deploy -f  
    - php bin/magento cache:clean  
    
# How to see the result?
Go to the backend
On the magento admin panel, you navigate to the 
STORES -> Settings -> Configuration -> Aligent -> Chat Configuration