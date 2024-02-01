# WP-SSO
WordPress SSO /User Integration/

Requirements:
- PHP 7.4
- WordPress in your localhost [FTP]
- IPB/IPS

Instalation:
- Import "wp_api" to public_html
- add the plugin in IPB/IPS
- add script in wordpress configuration for cookies.

Add this code in "wp-config.php"
```php
/**Enable Cookies*/
define('COOKIE_DOMAIN', $_SERVER['HTTP_HOST'] );
define( 'COOKIE_DOMAIN', '.your-site.com' );
``` 

- done!
The script works and does not need a monthly update to continue its work. It allows the integration that connects the two accounts via an API.
If you need help, join my >> Discord.BG-GAMER.com << Discord server! 
