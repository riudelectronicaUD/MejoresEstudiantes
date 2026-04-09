# Mejores Estudiantes - SharePoint UD

## Descripción

Este proyecto documenta la estructura, funcionamiento y componentes de la página **"Mejores Estudiantes"**, desarrollada en SharePoint Online para la Universidad Distrital Francisco José de Caldas.

La página tiene como propósito principal visualizar y gestionar la información de los estudiantes con mejor desempeño académico, permitiendo su consulta de manera clara, estructurada y accesible.

---

## Objetivos

### Objetivo general
Gestionar y mostrar información de estudiantes destacados académicamente dentro de la institución.

### Objetivos específicos
- Visualizar listados de estudiantes destacados
- Mostrar información estructurada (tablas, periodos, promedios)
- Facilitar la consulta para usuarios académicos y administrativos
- Servir como repositorio histórico académico

---

## Arquitectura del sistema

El sistema está basado en **Microsoft SharePoint Online**, utilizando:

- Sitio de comunicación
- Listas de SharePoint (base de datos)
- WebParts (componentes visuales)
- Control de permisos y accesos

---

## Estructura de la página

### Encabezado
- Logo institucional
- Nombre del sitio
- Navegación principal

### Contenido principal
- Introducción
- Listado de estudiantes
- Reconocimientos (matrículas de honor)
- Filtros por periodo, programa o facultad

---

## Modelo de datos

Los datos se almacenan en listas de SharePoint con los siguientes campos:

| Campo          | Tipo         | Descripción                     |
|---------------|-------------|---------------------------------|
| Nombre        | Texto       | Nombre del estudiante           |
| Código        | Texto/Número| Identificación                  |
| Programa      | Elección    | Carrera o programa académico    |
| Promedio      | Número      | Promedio acumulado              |
| Periodo       | Texto       | Ej: 2024-1                      |
| Reconocimiento| Texto       | Ej: Matrícula de honor          |

---

## Componentes técnicos

La página utiliza los siguientes elementos:

- WebPart de texto
- WebPart de listas
- Tablas HTML personalizadas
- Botones de navegación
- Bibliotecas de documentos

---

## Diseño e interfaz

- Diseño responsive
- Distribución en columnas (texto + tablas)
- Uso de estilos institucionales
- Tablas estilizadas mediante CSS y JavaScript

---

## Funcionalidades

- Visualización de datos académicos
- Organización por periodos
- Consulta rápida de información
- Integración con herramientas de Office 365

---

## Seguridad y permisos

- Acceso controlado (público o restringido)
- Permisos por roles (lectura y edición)
- Gestión mediante grupos institucionales

---

## Flujo de funcionamiento

1. El administrador carga datos en listas de SharePoint
2. SharePoint almacena la información
3. Los WebParts consumen y muestran los datos
4. El usuario final visualiza la información en la página

---

## Tecnologías utilizadas

- Microsoft SharePoint Online
- Office 365
- HTML5
- CSS3
- JavaScript

---

## Ventajas

- Centralización de información
- Fácil mantenimiento sin necesidad de desarrollo avanzado
- Integración con el ecosistema Microsoft
- Acceso desde cualquier dispositivo
- Trabajo colaborativo

---

## Posibles mejoras

- Implementar buscador dinámico
- Agregar filtros avanzados
- Incorporar visualizaciones gráficas
- Optimizar experiencia en dispositivos móviles
- Mejorar rendimiento de tablas

---

## Conclusión

La página "Mejores Estudiantes" es una solución eficiente para la gestión y visualización de información académica destacada, aprovechando las capacidades de SharePoint para ofrecer una plataforma accesible, organizada y funcional dentro del entorno institucional.

---

## Autor

Proyecto desarrollado como parte de prácticas académicas en ingeniería electrónica.

---

## Licencia

Este proyecto es de uso académico e institucional.
