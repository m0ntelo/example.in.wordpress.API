# ranek

## Plugin Install
```	
JWT Authentication for WP-API
```

## Configurate the secret key
```	
define('JWT_AUTH_SECRET_KEY','your-top-secret-key');
[You can use a string from here](https://wordpress.org/plugins/jwt-authentication-for-wp-rest-api/).
```

## Configurate cors support
```	
define('JWT_AUTH_CORS_ENABLE', true);
```

## PHP HTTP Authorization header enable
```	
RewriteEngine on
RewriteCond %{HTTP:Authorization} ^(.*)
RewriteRule ^(.*) - [E=HTTP_AUTHORIZATION:%1]
```

### Customize configuration
See [Configuration Reference](https://wordpress.org/plugins/jwt-authentication-for-wp-rest-api/).
