#PHP+APACHE+MYSQL on docker container#

git clone this

cd lamp-on-docker/

// modify .env as needed

docker-compose up -d

sudo chown -R mick:mick data

echo 'Works! <?php echo phpinfo();?>' >data/public_html/index.php

// visit localhost

Stop:
docker-compose down
