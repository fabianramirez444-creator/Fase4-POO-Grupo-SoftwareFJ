# Fase 4 - Componente Práctico: Prácticas Simuladas
## Sistema Integral de Gestión de Clientes, Servicios y Reservas - Software FJ

**Curso:** Programación (213023) - UNAD  
**Estudiante:** Wilson Fabián Ramírez Joya  
**Programa:** Ingeniería Electrónica  
**Grupo:** 192  
**Tutor(a):** Viky Erika Santanilla Parra  

---

### 📋 Descripción del Proyecto
Aplicación desarrollada en Python bajo el paradigma de **Programación Orientada a Objetos (POO)** para la empresa **Software FJ**, diseñada sin motores de base de datos relacionales[cite: 24, 49]. Utiliza estructuras en memoria (listas y diccionarios) y un control avanzado de excepciones con persistencia en archivos de registro (`errores.log`)[cite: 24, 49, 50].

### ⚙️ Requisitos Técnicos e Implementación
1. **Abstracción y Herencia:** Clases abstractas (`EntidadGeneral`, `Servicio`) y subclases especializadas (`ServicioSala`, `ServicioEquipo`, `ServicioAsesoria`) que implementan polimorfismo[cite: 26, 50].
2. **Encapsulamiento Estricto:** Atributos privados y protegidos expuestos mediante decoradores `@property` para garantizar la integridad de los datos del cliente y los servicios[cite: 26, 50].
3. **Manejo Avanzado de Excepciones:** Implementación rigurosa de bloques `try/except/else/finally`, excepciones personalizadas y encadenamiento de excepciones (`raise ... from ...`)[cite: 26, 50].
4. **Sistema de Logs:** Registro automático de eventos y errores detallados (incluyendo la traza de pila con `traceback`) en el archivo `errores.log`[cite: 26, 50].
5. **Simulación Completa:** Ejecución secuencial de 10 operaciones de prueba que validan registros correctos, datos erróneos, servicios inexistentes y manejo de excepciones sin interrumpir la estabilidad del programa[cite: 38, 39, 51].

### 📂 Archivos del Repositorio
- `Sistema_Software_FJ.py`: Código fuente principal estructurado en Python.
- `Sistema_Software_FJ.ipynb`: Cuaderno de Jupyter interactivo con el desarrollo completo.
- `errores.log`: Archivo de bitácora generado por la ejecución del sistema.
- `Sistema Integral de Gestión de Clientes.pdf`: Informe técnico formal bajo normas APA[cite: 23].
