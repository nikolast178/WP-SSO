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

/**Enable Cookies*/
define('COOKIE_DOMAIN', $_SERVER['HTTP_HOST'] );
/* developers */ 
define( 'WP_ALLOW_REPAIR', false );
define( 'WP_DEBUG', true );
define( 'WP_DEBUG_LOG', true );
define( 'WP_DEBUG_DISPLAY', false );

- done!
