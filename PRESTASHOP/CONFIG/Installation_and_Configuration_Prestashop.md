# CONFIGURATION

It is very important that we create a small file in APACHE save files.

We have to modify it. It must contain the port , the server name, server alias, Document root **very important**, error log and custom log.

Additionally we have two aliases. One is the web page and the other is the index.php script.

![MAIN_1](https://github.com/nic1551/Sintesi_ASIR/blob/master/PRESTASHOP/CONFIG/MAIN_CONFIG.PNG).

Onto the aliases.

Breaking down the first one. The only important option is the Require all granted. That way all the visitors that come to the page do not need special credentials to access the page.


The second one is open only to those who access the /tools section. It allows the autenticated users to enter the import tool.

![MAIN_2](https://github.com/nic1551/Sintesi_ASIR/blob/master/PRESTASHOP/CONFIG/MAIN_CONFIG_2.PNG).

![MAIN_3](https://github.com/nic1551/Sintesi_ASIR/blob/master/PRESTASHOP/CONFIG/MAIN_CONFIG_3.PNG).

