# API Testing

## What is this?
This folder contains REST API testing artifacts, including test cases and endpoint validations.

## Product / Functionality under test
- REST API (api_stand_tests)
- Endpoints for resource management and response validations

## Objective
Verify that API endpoints respond correctly with expected status codes, data and formats.

## Scope
**Included:**
- Status code validation (200, 201, 400, 404, etc.)
- JSON response structure verification
- Test cases for critical endpoints

**Not included:**
- API performance testing
- Advanced security or authentication testing

## Artifacts in this folder
| File | Description | Skill demonstrated |
|---------|-------------|---------------------|
| [View full repository](https://github.com/GhordyVargas/api_stand_tests) | API test cases and execution | Requests, Python, test design |

## Key decisions
- **Prioritized critical endpoints** that directly impact product functionality
- **Focused on status code validation** as they are key indicators of API health
- **Used Python + Requests** as they are lightweight and effective for API testing

## Results
- Documented test cases for API endpoints
- Status code and response structure validations
- Test execution with results reporting

## What would I improve next?
- Add load and performance testing
- Implement more robust JSON schema validations
- Integrate with CI/CD for automatic execution

---

# API Testing

## ¿Que es esto?
Esta carpeta contiene artefactos de testing de APIs REST, incluyendo casos de prueba y validaciones de endpoints.

## Producto / Funcionalidad bajo prueba
- API REST de stand (api_stand_tests)
- Endpoints para gestion de recursos y validaciones de respuestas

## Objetivo
Verificar que los endpoints de la API respondan correctamente con los status codes, datos y formatos esperados.

## Alcance
**Incluido:**
- Validacion de status codes (200, 201, 400, 404, etc.)
- Verificacion de estructura de respuestas JSON
- Casos de prueba para endpoints criticos

**No incluido:**
- Testing de rendimiento de API
- Pruebas de seguridad o autenticacion avanzada

## Artefactos en esta carpeta
| Archivo | Descripcion | Habilidad demostrada |
|---------|-------------|---------------------|
| [Ver repositorio completo](https://github.com/GhordyVargas/api_stand_tests) | Casos de prueba y ejecucion de API testing | Requests, Python, test design |

## Decisiones clave
- **Priorice endpoints criticos** que impactan directamente la funcionalidad del producto
- **Enfoque en validacion de status codes** porque son indicadores clave de salud de la API
- **Use Python + Requests** por ser herramientas ligeras y efectivas para API testing

## Resultados
- Casos de prueba documentados para endpoints de la API
- Validaciones de status codes y estructura de respuestas
- Ejecucion de pruebas con reporte de resultados

## ¿Que mejoraria despues?
- Agregar pruebas de carga y rendimiento
- Implementar validaciones de schema JSON mas robustas
- Integrar con herramientas de CI/CD para ejecucion automatica
