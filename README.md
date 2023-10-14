#PHP+APACHE+MYSQL on docker container#

git clone this

cd lamp-on-docker/

// modify .env as needed

docker-compose up -d

sudo chown -R mick:mick data

echo 'Works! <?php echo phpinfo();?>' >data/public_html/index.php

// (web) localhost:8080

// (phpmyadmin) localhost:3001 

Stop:
docker-compose down
