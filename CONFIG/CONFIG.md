# WHAT IS IT?

There are 3 scripts that generate a basic input system to the database via web. The main script is index.php 
![INDEX_1](https://github.com/nic1551/Sintesi_ASIR/blob/master/CONFIG/INDEX.PHP_1.PNG).
![INDEX_2](https://github.com/nic1551/Sintesi_ASIR/blob/master/CONFIG/INDEX.PHP_2.PNG).

How the script is seen on a browser: 
![INDEX_3](https://github.com/nic1551/Sintesi_ASIR/blob/master/CONFIG/INDEX.PHP_3.PNG).

## CONFIG.PHP
### WHAT IS IT AND WHAT DOES IT DO?
A very simple function that connects to the prestashop database.
![CONFIG_1](https://github.com/nic1551/Sintesi_ASIR/blob/master/CONFIG/CONFIG.PHP_1.PNG).

## FUNCTIONS.PHP
### WHAT IS IT AND WHAT DOES IT DO?
A little more complex than the last script. What this script does is select rows and import them into the database.
![FUNCTION_1](https://github.com/nic1551/Sintesi_ASIR/blob/master/CONFIG/FUNCTIONS.PHP_1.PNG).
Lets break it down:

Inside the first IF there are some parametres that allow the script identify a temporary name to the input file. The second IF only runs when the file size is more than 0 bytes. In other words it will not allow empty files logically. Moving on to the main part of the program. 

The import file must contain the following in a specfic order. id_product, ean13, price, show_price, reference. The delimiter must be a comma(,).

Then a small pop up windows will appear with a message. If the values were imported correctly the pop up will show: CSV file has  been sucessfully imported. If not then another message will appear: Invalid File: Please Upload CSV file.

#### FUNCTION GET ALL RECORDS:
First the functions requires a call do the getdb function located in CONFIG.PHP. Once connected it will show all the recent records that we have inserted into the database
![FUNCTION_2](https://github.com/nic1551/Sintesi_ASIR/blob/master/CONFIG/FUNCTIONS.PHP_2.PNG).
Finally it will then export the records into a custom designed table
![FUNCTION_3](https://github.com/nic1551/Sintesi_ASIR/blob/master/CONFIG/FUNCTIONS.PHP_3.PNG).


# CONFIGURATION OF TH[alt text]E MAIN SCRIPT

