# Getting Started
## Step 1:

```javascript 
sudo apt update
````

## Step 2: 

```javascript 
sudo apt install php-cli unzip
````

## Step 3:

```javascript 
cd ~
````

## Step 4: curl -sS https://getcomposer.org/installer -o /tmp/composer-setup.php

## Step 5: HASH=`curl -sS https://composer.github.io/installer.sig`

## Step 6: php -r "if (hash_file('SHA384', '/tmp/composer-setup.php') === '$HASH') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;”

## Step 7:

```javascript 
sudo php /tmp/composer-setup.php --install-dir=/usr/local/bin --filename=composer
````

> To Check Composer Version :: composer -v
