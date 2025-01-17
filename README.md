## API Starter

### Pre-installed package

- Sanctum with API only
- Sail with SSL
- Laravel Query Builder by Spatie
- Laravel Settings by Spatie


### Requirements

- PHP 8.4
- Docker for development

### Getting Started

- `composer install` to install dependencies.
- Copy `.env.example` to `.env` then modify it appropriately.
  - Modify `SSL_DOMAIN` value to your local development hostname.
- `sail up` to start container.
- `sail down` to remove container.

### Troubleshooting

Common issues and resolutions you may encounter during development.


#### SSL is not registering in development

- Remove the nginx volume from docker then `sail up` to regenerate the certificate.
