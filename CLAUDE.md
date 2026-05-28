---
project_name: APIREST-PHP-POO-JWT-MIDDLEWARE-Documentar
project_type: "academic-api-rest-documentation"
complexity: "medium"
technologies: "php, slim, jwt, middleware, mariadb, php-oop"
description: "Documentación de API REST con PHP Slim, POO + JWT + Middleware - Versión 1 a 6"
status: "completed"
role_match: "Backend Developer, PHP Developer, API Developer"
---

# 📌 APIREST-PHP-POO-JWT-MIDDLEWARE-Documentar

## 🎯 Descripción

Documentación completa de implementación de **API REST con PHP Slim**.
Contiene 6 versiones que evolucionan desde API básica hasta JWT + POO + Middleware.

**Directorios principales:**
- `apirestV1/` - API REST básica
- `apirestV2-POO/` - POO
- `apirestV3-MW/` - Middleware
- `apirestV4-MW-POO/` - Middleware + POO
- `apirestV5-JWT/` - JWT
- `apirestV6-JWT-MW-POO/` - JWT + Middleware + POO (final)

## 🛠️ Tecnologías

- **Lenguaje:** PHP 7.x/8.x
- **Framework:** Slim Framework 3/4
- **Database:** MariaDB/MySQL (schema en `cdcol.sql`)
- **Security:** JWT (JSON Web Tokens)
- **Padrón:** POO (Programación Orientada a Objetos)
- **Middleware:** Custom middleware para autenticación, logging, etc.

## 📁 Estructura del Proyecto

```
APIREST-PHP-POO-JWT-MIDDLEWARE-Documentar/
├── CLAUDE.md              ← Este archivo
├── .claude/               ← Configuración
│   ├── settings.json
│   ├── agents/
│   ├── commands/
│   ├── hooks/
│   ├── rules/
│   └── skills/
├── README.md
├── composer.json
├── cdcol.sql              ← Base de datos schema
├── leeme para la documentación.txt
├── apidoc.json            ← Documentación API
├── apirestV1/             ← API básica
├── apirestV2-POO/         ← + POO
├── apirestV3-MW/          ← + Middleware
├── apirestV4-MW-POO/      ← + POO
├── apirestV5-JWT/         ← + JWT
└── apirestV6-JWT-MW-POO/  ← Versión final completa
```

## 🗄️ Base de Datos

`cdcol.sql` contiene el schema de la base de datos con:
- Tablas de productos, categorías
- Tablas de usuarios y roles
- Relación entre tablas

## 🚀 Comandos Útiles

```bash
# Instalar dependencias (PHP)
composer install

# Correr servidor local
php -S localhost:8000

# Migrar base de datos
mysql -u usuario -p password db < cdcol.sql

# Documentar API
php vendor/bin/apidoc generate
```

## 💡 Puntos Clave para el Desarrollador

1. **Evolución de versiones:** Cada versión añade funcionalidad
2. **POO:** Implementar principios SOLID
3. **Middleware:** Crear middleware reutilizable
4. **JWT:** Autenticación segura con tokens
5. **Documentación:** Mantener `apidoc.json` actualizado
6. **Testeo:** Pruebas unitarias con PHPUnit

## 🔒 Seguridad y restricciones

- **NUNCA** hardcodear JWT secrets
- **NUNCA** commitear credenciales de BD
- Validar y sanitizar todos los inputs
- Usar prepared statements (ni SQL injection)

## 📝 Contexto del Proyecto

- **Asignatura:** Programación III
- **Periodo:** Actual/2018
- **Tipo:** API REST + Documentación
- **Enfoque:** PHP Slim, POO, JWT, Middleware
- **Audiencia:** Estudiantes de backend

---
*Memoria de proyecto generada por Claude*
