# Automatización de Horarios y Turnos

## Descripción general

Este proyecto busca automatizar la gestión de horarios y turnos de trabajo para organizaciones que operan con personal rotativo, como retail, clínicas, call centers y restaurantes. La idea principal es reemplazar la planificación manual con un sistema que permita asignar turnos de manera más eficiente, segura y trazable.

La solución propuesta reduce errores humanos, optimiza el tiempo del personal encargado y ayuda a cumplir con las normas laborales y de cobertura.

---

## Contexto

Muchas empresas aún organizan los horarios de forma manual, utilizando hojas de cálculo o incluso papel. En estos procesos, un encargado debe revisar la disponibilidad de cada trabajador, considerar horas máximas y mínimas, respetar días de descanso obligatorios y asegurar la cobertura necesaria por turno.

Este proceso se repite cada semana y se vuelve más complicado a medida que crece el número de empleados. Con equipos más grandes, la asignación manual genera más errores y consume más tiempo.

---

## Problemática

La organización manual de turnos presenta varios problemas recurrentes:

- Errores humanos frecuentes: se pueden asignar dos personas al mismo horario crítico o dejar vacantes sin cobertura.
- Tiempo perdido: construir el horario semanal puede tomar varias horas y cualquier cambio inesperado obliga a rehacerlo.
- Falta de trazabilidad: los cambios y canjes de turno se coordinan por mensaje o verbalmente y no quedan registrados.
- Comunicación tardía: los horarios suelen publicarse con poca anticipación, lo que genera reclamos y ausentismo.
- Sobrecarga desigual: algunos trabajadores reciben más horas o turnos difíciles que otros sin una distribución equilibrada.

---

## Solución propuesta

Se propone desarrollar un sistema de software que automatice la generación y administración de turnos, incorporando las siguientes funciones:

- Registro de disponibilidad, roles y restricciones de cada trabajador.
- Generación automática de un horario semanal o mensual, respetando reglas de negocio.
- Validación de cobertura mínima, descansos obligatorios y límites legales de jornada.
- Gestión de solicitudes de cambio o canje de turno con aprobación del encargado.
- Notificación automática del horario publicado y de sus modificaciones.
- Historial claro de asignaciones, cambios y aprobaciones.

---

## Alcance funcional del sistema

El sistema se divide en cinco módulos principales:

### 1. Gestión de usuarios
- Creación de cuentas y perfiles.
- Roles y permisos para administrador, jefe de turno y trabajador.
- Autenticación y control de acceso.

### 2. Gestión de trabajadores
- Registro de datos personales y laborales.
- Disponibilidad y restricciones del personal.
- Información de contrato y rol asignado.

### 3. Gestión de horarios
- Generación y publicación de turnos.
- Solicitudes de cambio o canje entre trabajadores.
- Aprobación de cambios por parte del encargado.

### 4. Cumplimiento de la jornada laboral
- Validación automática de descansos mínimos.
- Control de horas máximas diarias y semanales.
- Alertas ante incumplimientos legales o de negocio.

### 5. Reportería estadística
- Indicadores de horas trabajadas.
- Análisis de ausentismo.
- Monitoreo del cumplimiento normativo.
- Evaluación de carga de trabajo por trabajador y periodo.

---

## Estructura de Desglose del Trabajo (EDT)

La EDT del proyecto organiza el trabajo en cinco fases principales:

- Gestión: actas, cronograma, roles del equipo y reportes de avance.
- Requisitos: entrevistas con el cliente, necesidades del negocio y trazabilidad.
- Diseño: modelos de clases, base de datos, prototipo de interfaz y patrones de diseño.
- Desarrollo: módulos funcionales del sistema y lógica de asignación automática.
- Despliegue: pruebas, documentación y capacitación final.

Esta estructura permite llevar el proyecto de forma ordenada y alineada con el desarrollo curricular.

---

## Diagrama de Ishikawa

El diagrama de causa-efecto identifica las principales causas detrás de los errores y retrasos en la asignación manual de turnos.

### Causas principales

#### Personas
- Alta rotación del personal.
- Cambios frecuentes en la disponibilidad.
- Falta de capacitación del encargado.

#### Proceso
- Ausencia de reglas claras y estandarizadas.
- Falta de flujo formal para aprobar cambios.

#### Herramientas
- Dependencia de hojas de cálculo o papel.
- Pérdida de información por uso de mensajería informal.

#### Políticas
- Normativa laboral compleja y cambiante.
- Licencias médicas y ausencias de última hora que alteran la planificación.

---

## Objetivo del proyecto

El objetivo del proyecto es crear una solución tecnológica que permita asignar turnos de forma automática, ordenada y conforme a las reglas laborales, reduciendo el esfuerzo manual y mejorando la experiencia tanto para la empresa como para los trabajadores.

---

## Equipo

- Benjamin Candia
- Ignacio Figueroa
- Endert Guerrero
- Felipe Ochoa
- Jorge Pinto
- Antonia Valdebenito

**Profesor:** Álvaro Sánchez Colmenares

**Fecha de entrega:** 23 de agosto de 2026
