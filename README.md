# 🧮 Calculadora CI — PHP + PHPUnit + GitHub Actions

![PHP CI](https://github.com/julianalexisrivera-crypto/calculadora-ci/actions/workflows/php-ci.yml/badge.svg)

## 📁 Estructura del Proyecto

```text
calculadora-ci/
├── .github/
│   └── workflows/
│       └── php-ci.yml        # Pipeline de integración continua
├── src/
│   └── Calculadora.php       # Lógica de la calculadora
├── tests/
│   └── CalculadoraTest.php   # Pruebas unitarias con PHPUnit
├── composer.json             # Dependencias del proyecto
└── README.md                 # Documentación
```               # Documentación

## 🛠️ Tecnologías Utilizadas

| Tecnología | Versión | Uso |
|---|---|---|
| PHP | 8.2 | Lenguaje principal |
| PHPUnit | ^10.0 | Framework de pruebas unitarias |
| Composer | Latest | Gestor de dependencias |
| GitHub Actions | — | Integración continua (CI) |

## 🧪 Pruebas Unitarias

El proyecto cuenta con **5 pruebas unitarias** que validan todas las operaciones de la calculadora:

| Prueba | Descripción | Estado |
|---|---|---|
| `testSuma` | Verifica que 2 + 3 = 5 | ✅ |
| `testResta` | Verifica que 4 - 3 = 1 | ✅ |
| `testMultiplicacion` | Verifica que 4 × 3 = 12 | ✅ |
| `testDivision` | Verifica que 6 / 3 = 2 | ✅ |
| `testDivisionPorCeroLanzaExcepcion` | Verifica que dividir por cero lanza `InvalidArgumentException` | ✅ |

## 🚀 Ejecutar el Proyecto Localmente

### Requisitos previos
- PHP 8.2 o superior instalado
- Composer instalado

### Pasos

**1. Clonar el repositorio**
```bash
git clone https://github.com/julianalexisrivera-crypto/calculadora-ci.git
cd calculadora-ci
```

**2. Instalar dependencias**
```bash
composer install
```

**3. Ejecutar las pruebas**
```bash
./vendor/bin/phpunit tests
```

**4. Resultado esperado**
## 🔗 URL del Repositorio

👉 https://github.com/julianalexisrivera-crypto/calculadora-ci

## 👨‍💻 Creador

**Julián Alexis Rivera Fernández**  
Estudiante de Tecnología en Desarrollo de Software