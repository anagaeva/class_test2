#This file below checks if the jump file created
if [ -f /mnt/jump ]
then
        echo "1 , Jump file is created " >> /var/www/html/index.html 2> /dev/null
else
        echo "2 , Jump file is not created" >> /var/www/html/index.html 2> /dev/null
fi
