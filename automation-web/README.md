## Web Test Automation – Proyecto de AutomatizaciÃ³n con Selenium

### Objetivo
Automatizar escenarios crÃ©ticos de una aplicaciÃ³n web para validar su funcionamiento de manera repetible y eficiente.

### Alcance
Se automatizaron los siguientes flujos:
- Inicio de sesiÃ³n (login).
- ValidaciÃ³n de elementos y funcionalidades clave.
- NavegaciÃ³n entre pÃ¡ginas principales.

### Mi participaciÃ³n
DiseÃ±Ã© los escenarios de prueba, escribÃ© los scripts de automatizaciÃ³n y organicÃ© la ejecuciÃ³n de las pruebas utilizando Selenium con Python.

### Escenarios automatizados
- **Login exitoso:** Credenciales vÃ¡lidas que permiten el acceso.
- **Login fallido:** Credenciales incorrectas con mensaje de error apropiado.
- **ValidaciÃ³n de campos:** Campos obligatorios y formatos esperados.
- **NavegaciÃ³n:** VerificaciÃ³n de redirecciones y elementos visibles.

### Buenas prÃ¡cticas aplicadas
- **Selectores estables:** Uso de IDs, names y atributos data-test.
- **Esperas explÃ©citas:** Para sincronizaciÃ³n adecuada con el DOM.
- **Funciones reutilizables:** Para acciones comunes como login y navegaciÃ³n.
- **OrganizaciÃ³n modular:** SeparaciÃ³n de pÃ¡ginas (Page Objects), tests y utilidades.

### Estructura del proyecto
```
âºº main.py
âºº pages/
âºº   ââºº [Page Objects para cada pÃ¡gina]
âºº tests/
âºº   ââºº [Scripts de prueba automatizados]
âºº   ââºº utils/
âºº       ââºº [Funciones auxiliares]
```

### Herramientas utilizadas
- **Selenium WebDriver:** Para automatizaciÃ³n de navegador.
- **Python:** Lenguaje de programaciÃ³n.
- **Chrome/Firefox:** Navegadores para ejecuciÃ³n de pruebas.

### Evidencias
- Scripts de automatizaciÃ³n en Python.
- Page Objects organizados por pÃ¡gina.
- Casos de prueba automatizados.
- [Repositorio completo](https://github.com/GhordyVargas/Automatizacion-de-Pruebas-Web)

### Aprendizaje
Este proyecto me permitiÃ³ practicar la transformaciÃ³n de casos manuales en pruebas automatizadas y comprender cÃ³mo mantener scripts mÃ¡s legibles y reutilizables. TambiÃ©n fortalecÃ© mi habilidad para identificar selectores estables y manejar esperas de manera efectiva.

---

**Repositorio relacionado:** [Automatizacion-de-Pruebas-Web](https://github.com/GhordyVargas/Automatizacion-de-Pruebas-Web)
