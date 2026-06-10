# Evaluación Sumativa III - Análisis Estático de Código con SonarQube

**Asignatura:** Calidad de componentes de Software
**Sección:** AOL-ELE-TILE11-C20
**Docente:** Valery Emy Belén Rodríguez Castillo
**Integrantes:** Maycol Ignacio Fuentes Sandoval - Agustín Ernesto Mieville Vogt - José Francisco Galdámez Bórquez
**Fecha de entrega:** 14-06-2026

---

## Objetivo de la Evaluación
Este repositorio contiene el código del proyecto **Ticket Sales Dashboard**, el cual fue utilizado como caso práctico para esta evaluación sumativa. 

El propósito de esta entrega es evidenciar la aplicación de análisis estático de código mediante **SonarQube** sobre un proyecto JavaScript real, identificar y corregir los *issues* intencionales, y vincular dichos hallazgos con los principios fundamentales de un Sistema de Gestión de Calidad (SGC).

## Trabajo Realizado en el Código
Siguiendo las instrucciones del caso práctico, el equipo ejecutó un análisis de calidad completo utilizando SonarQube mediante Docker. Se trabajó específicamente sobre el archivo `js/app.js`, resolviendo los siguientes hallazgos:

* **Maintainability:** Corrección de malas prácticas de ECMAScript (reemplazo de `var` por `let`/`const`) y eliminación de comentarios "TODO" inactivos.
* **Reliability:** Aplicación de métodos estrictos de validación y conversión (`Number.parseInt` y `Number.isNaN`) para evitar comportamientos inesperados en el ingreso de datos.
* **Flujo Lógico:** Detección y eliminación de código inalcanzable (`Unreachable code`) provocado por retornos (`return;`) mal posicionados.

## Relación con los Principios SGC
La depuración de este código no solo resuelve problemas técnicos, sino que asegura los requerimientos específicos del producto de software (como la correcta validación de entradas y la gestión del stock). Las justificaciones detalladas y la selección de los tres principios SGC se encuentran documentadas en nuestro informe escrito y sustentadas en el video explicativo grupal.

## Despliegue del Proyecto
Para visualizar el dashboard con las correcciones ya implementadas, simplemente basta con clonar o descargar este repositorio y abrir el archivo `index.html` en cualquier navegador web.
