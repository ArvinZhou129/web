
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://ArvinZhou.github.io/web/index.html$1 [R,L]
