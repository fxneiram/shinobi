# Fxneiram Shinobi

Un sistema basado en roles y permisos, simple y liviano para el sistema de Authorization de Laravel. Desarrollado originalmente para [FusionCMS](https://github.com/fusioncms/fusioncms), un sistema de gestión de contenido de código abierto.

- Cada usuario puede tener cero o más permisos.
- Cada usuario puede tener cero o más roles.
- Cada rol puede tener cero o más permisos.
- Cada rol puede tener uno de dos permisos especiales, `all-access` y `no-access`

# Documentación

## Instalación
Simplemente instale el paquete a través de Composer. Desde aquí, el paquete se registrará automáticamente en el ServiceProvider.

```
composer require fxneiram/shinobi
```

## Config
Para publicar el archivo de configuración, ejecute lo siguiente:

```
php artisan vendor:publish --provider="Fxneiram\Shinobi\ShinobiServiceProvider" --tag="config"
```

## Contributing
Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Testing
Ejecute los test con PHPUnit:

```bash
vendor/bin/phpunit
```

## Security
Si descubre algún problema relacionado con la seguridad, envíe un correo electrónico a fxneiram@gmail.com directamente en lugar de usar el rastreador de problemas.

## Credits
- [Shea Lewis](https://github.com/kaidesu)
- [All Contributors](../../contributors)

## License
The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
