# Web Automation

## ¿Qué·´ es esto?
Esta carpeta contiene artefactos de automatizacion de pruebas web end-to-end para aplicaciones de e-commerce y web apps.

## Producto / Funcionalidad bajo prueba
- Aplicacion web de e-commerce (Urban Grocers)
- Funcionalidades de carrito de compras, checkout y navegacion

## Objetivo
Verificar que las funcionalidades criticas del sitio web funcionen correctamente mediante automatizacion de pruebas con Selenium y Python.

## Alcance
**Incluido:**
- Automatizacion de flujos de usuario (login, agregar al carrito, checkout)
- Validaciones de UI y funcionalidad
- Implementacion de Page Object Model (POM)

**No incluido:**
- Testing de API backend
- Pruebas de rendimiento o carga

## Artefactos en esta carpeta
| Archivo | Descripcion | Habilidad demostrada |
|---------|-------------|---------------------|
| [Ver repositorio completo](https://github.com/GhordyVargas/Automatizacion-de-Pruebas-Web) | Scripts de automatizacion web | Selenium, Python, POM |
| [Ver repositorio completo](https://github.com/GhordyVargas/qa-project-Urban-Grocers-app-es) | Automatizacion de e-commerce | Selenium, Python, test cases |

## Decisiones clave
- **Priorice automatizacion de flujos de usuario** porque son los mas criticos para la experiencia del cliente
- **Use Page Object Model** para hacer el codigo mantenible y reutilizable
- **Enfoque en Python + Selenium** por ser herramientas estandar en la industria y faciles de mantener

## Resultados
- Scripts de automatizacion funcionales para flujos clave de e-commerce
- Codigo estructurado con POM para facil mantenimiento
- Validaciones de UI, textos y funcionalidad implementadas

## ¿Que mejoraria despues?
- Agregar tests de regresion automatizados en CI/CD
- Expandir cobertura a mas funcionalidades del sitio
- Implementar reporting automatico de resultados
