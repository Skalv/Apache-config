Apache-config
=============

Apache config


.htaccess :

<code>
  <IfModule mod_rewrite.c>
    # Options -MultiViews
    
    # RewriteEngine On
    # #RewriteBase /path/to/app
    # RewriteCond %{REQUEST_FILENAME} !-f
    # RewriteRule ^ index.php [QSA,L]
    FallbackResource /index.php
  </IfModule>
</code>
