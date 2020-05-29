# rooter
Un middleware pour rediriger vers une page 500 custom si une exception n'est pas catché

## Installation

Via composer
```
composer require veka-server/redirect-error-500
```

## Utilisation

Initialisation
```php
// Creation du middleware
$middleware = new \VekaServer\RedirectError500\RedirectError500();
```
