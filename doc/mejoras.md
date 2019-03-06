# Mejoras para hacerle

- Sacar db:seed del Procfile.
- Agregar configuraciones por defecto para Heroku:Bucketeer:
  - gem aws-sdk-s3
  - Configuración en storage.yml
  - config.active_storage.service = :amazon en config/environments/production.rb
- gem mini_magick
