## API Testing – Proyecto de ValidaciÃ³n de API REST

### Objetivo
Validar el comportamiento de una API REST, comprobando que los endpoints respondieran correctamente ante solicitudes vÃ¡lidas e invÃ¡lidas.

### Alcance
Se probaron los endpoints disponibles para:
- Obtener recursos.
- Crear nuevos registros.
- Actualizar datos existentes.
- Eliminar registros.

### Mi participaciÃ³n
DiseÃ±Ã© y ejecutÃ© pruebas en Postman para validar cada endpoint, documentando las respuestas y comportamientos observados.

### Estrategia de pruebas
- **Escenarios positivos:** Solicitudes con datos vÃ¡lidos y completos.
- **Escenarios negativos:** Datos incompletos, incorrectos o invÃ¡lidos.
- **Casos de borde:** Valores lÃ©mite y combinaciones inusuales.

### Validaciones realizadas
- CÃ³digos de estado HTTP (200, 201, 400, 404, 500).
- Estructura JSON de las respuestas.
- Presencia y formato de campos obligatorios.
- Mensajes de error coherentes.
- Comportamiento ante parÃ¡metros ausentes.

### Herramientas utilizadas
- **Postman:** DiseÃ±o y ejecuciÃ³n de colecciones de pruebas.
- **Variables de entorno:** Para manejar diferentes configuraciones.
- **Scripts de validaciÃ³n:** Para verificar respuestas automÃ¡ticamente.

### Hallazgos
- Se identificaron comportamientos esperados en todos los endpoints probados.
- Las validaciones confirmaron que la API maneja correctamente tanto escenarios positivos como negativos.

### Evidencias
- ColecciÃ³n de Postman con todos los casos de prueba.
- DocumentaciÃ³n de los endpoints probados.
- Capturas de las respuestas obtenidas durante la ejecuciÃ³n.

### Aprendizaje
Este proyecto me permitiÃ³ fortalecer mi capacidad para diseÃ±ar escenarios positivos y negativos, analizar respuestas REST y detectar diferencias entre el comportamiento esperado y el real. TambiÃ©n mejorÃ© mi habilidad para documentar pruebas de API de manera estructurada y profesional.

---

**Repositorio relacionado:** [api_stand_tests](https://github.com/GhordyVargas/api_stand_tests)
