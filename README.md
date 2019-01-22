# Apache2-www-and-subsequent-folder-permissions

sudo adduser $USER www-data  
sudo chown root:root /var/www  
sudo chown -R $USER:www-data /var/www/*  
sudo chmod -R 755 /var/www  

sudo a2enmod rewrite  
sudo chown -R www-data /var/www  
