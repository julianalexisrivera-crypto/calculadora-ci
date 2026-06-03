# Calculadora CI - PHP + PHPUnit

![PHP CI](https://github.com/julianalexisrivera-crypto/calculadora-ci/actions/workflows/php-ci.yml/badge.svg)

## Descripción
Calculadora en PHP con pruebas unitarias automatizadas e integración continua mediante GitHub Actions.

## URL del Repositorio
https://github.com/julianalexisrivera-crypto/calculadora-ci

## Tecnologías
- PHP 8.2
- PHPUnit 10
- Composer
- GitHub Actions (CI)

## Cómo ejecutar las pruebas localmente
```bash
composer install
./vendor/bin/phpunit tests
```

## Flujo TDD aplicado
1. `ci: estructura inicial del proyecto con archivos base`
2. `ci: configurado pipeline github actions`
3. `test: prueba de division agregada` → ❌ Red
4. `fix: correccion metodo dividir` → ✅ Green
5. `test: prueba division por cero lanza excepcion` → ❌ Red
6. `fix: validacion division por cero con excepcion` → ✅ Green