For WordPress Environment Settings: 

PORT 80

Compose Path:  
`./wordpress/docker-compose.yml`

`WORDPRESS_DB_HOST=`  
`WORDPRESS_DB_NAME=`  
`WORDPRESS_DB_USER=`  
`WORDPRESS_DB_PASSWORD=`  
`WORDPRESS_DB_CHARSET=utf8`  
`WORDPRESS_DB_COLLATE=''`  
`WORDPRESS_TABLE_PREFIX=wp_`  
`WORDPRESS_DEBUG=false`  
`WORDPRESS_CONFIG_EXTRA=''`

For debug:  
`WORDPRESS_CONFIG_EXTRA=define('WP_DEBUG_LOG', true); define('WP_DEBUG_DISPLAY', true); define('SCRIPT_DEBUG', true); define('SAVEQUERIES', true);`  

For PhpMyAdmin Environment Settings:

PORT 80

Compose Path:  
`./phpmyadmin/docker-compose.yml`

`PMA_HOST=`  