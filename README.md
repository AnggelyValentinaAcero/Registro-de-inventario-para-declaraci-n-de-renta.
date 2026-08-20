# Registro de inventario para declaración de renta. 

Este proyecto consiste en el desarrollo de una aplicación de software orientada a apoyar el proceso de declaración de renta en Colombia mediante la organización y gestión de información relacionada con los contribuyentes, patrimonio, ingresos e inventarios.

El sistema contempla diferentes funcionalidades dependiendo del tipo de contribuyente. Para los contribuyentes que tienen actividades relacionadas con negocios, se incluye la gestión de inventarios, movimientos, métodos de costeo y generación de reportes.

El proyecto busca organizar la información necesaria para facilitar el manejo de los datos utilizados durante el proceso de declaración de renta.

----

## Objetivo

Identificar, organizar y gestionar la información necesaria para el desarrollo de una aplicación de inventarios que apoye el proceso de declaración de renta en Colombia.

---

## Objetivos Específicos 

- Gestionar la información de los contribuyentes.
- Registrar y organizar información relacionada con el patrimonio.
- Registrar fuentes de ingresos.
- Gestionar productos y categorías de inventario cuando corresponda.
- Registrar movimientos de inventario.
- Gestionar proveedores y documentos soporte.
- Aplicar métodos de costeo como PEPS y promedio ponderado.
- Generar información y reportes relacionados con el cierre del periodo fiscal.

---

## Funcionalidades

### Gestión de contribuyentes
Permite registrar y gestionar la información básica de los contribuyentes.

### Gestión de patrimonio
Permite registrar información relacionada con los activos y el patrimonio del contribuyente.

### Gestión de ingresos
Permite registrar las diferentes fuentes de ingreso.

### Gestión de inventario
Para los usuarios a los que aplique, permite:

- Registrar productos.
- Organizar productos por categorías.
- Registrar entradas y salidas.
- Gestionar proveedores.
- Registrar documentos soporte.
- Consultar movimientos.
- Actualizar existencias.

### Métodos de costeo

El sistema contempla métodos de costeo como:

- PEPS (Primeras Entradas, Primeras Salidas).
- Promedio ponderado.

### Reportes

El sistema contempla la generación de información relacionada con:

- Kardex.
- Saldo final del inventario.
- Resumen de patrimonio e ingresos.
- Información relacionada con el formato 2517 cuando aplique.

---

## Usuarios del sistema

El proyecto contempla diferentes tipos de contribuyentes:

- **Asalariado:** usuario que gestiona principalmente información relacionada con patrimonio e ingresos.
- **Independiente:** usuario que puede gestionar patrimonio, ingresos e inventario.
- **Mixto:** usuario que puede gestionar patrimonio, ingresos e inventario.

La gestión del inventario se contempla principalmente para los contribuyentes que desarrollan actividades relacionadas con negocios.

---

##   Arquitectura del proyecto

La aplicación se plantea utilizando una arquitectura de tres capas:

1. **Capa de presentación:** encargada de la interacción con el usuario.
2. **Capa de lógica de negocio:** encargada de procesar las reglas y operaciones del sistema.
3. **Capa de datos:** encargada del almacenamiento y gestión de la información.

### Tecnologías propuestas

- **Lenguaje:** Python
- **Framework:** Django
- **Base de datos:** MySQL
- **Control de versiones:** Git
- **Repositorio:** GitHub

La aplicación se organizará mediante diferentes módulos de Django, entre ellos:

- `patrimonio`
- `inventario`
- `movimientos`
- `reportes`

---

##     Entidades del sistema

El proyecto contempla entidades relacionadas con los diferentes módulos:

### Patrimonio
- Contribuyente
- Activo
- FuenteIngreso

### Inventario
- Producto
- Categoría
- MétodoCosteo

### Movimientos
- Movimiento
- Proveedor
- DocumentoSoporte

### Reportes
- PeriodoFiscal

---

##     Modelo de desarrollo

El proyecto utilizará un modelo de desarrollo incremental.
El sistema será desarrollado mediante diferentes incrementos funcionales:

1. Gestión de productos y categorías.
2. Registro de movimientos de inventario.
3. Cálculo del costo de ventas.
4. Generación de reportes de cierre del periodo fiscal.

---

##  Integrantes

- Valentina Acero
- Quianwei chen
- Jairo Naranjo

---
