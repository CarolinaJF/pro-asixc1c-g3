# Proyecto Transversal ASIXc  
## Administración de Sistemas Informáticos en Red  
**Grupo:** ASIXc1C - G3  
**Curso:** 2024/2025  
**Profesorado:** Equipo docente ASIXc1C  

---

# Índice


-
- [Diseño e implementación de la base de datos](src/pro_4/4.md)
- [Sostenibilidad y eficiencia energética](src/pro_5/5.md)

## Índice

1. [Introducción](#introducción)  
2. [Descripción del proyecto](#descripción-del-proyecto)  
3. [Objetivos del proyecto](#objetivos-del-proyecto)  
4. [Tarea a realizar](#tarea-a-realizar)  
5. [Propuesta de CPD](#propuesta-de-cpd)  
    - [Ubicación física del CPD](#ubicación-física-del-cpd)  
    - [Introducción y definición de la empresa](#introducción-y-definición-de-la-empresa)  
    - [Objetivo del proyecto](#objetivo-del-proyecto)  
    - [Justificación de la arquitectura elegida](#justificación-de-la-arquitectura-elegida)  
    - [Distribución física y técnica](#distribución-física-y-técnica)  
    - [Sistemas de climatización](#sistemas-de-climatización)  
    - [Medidas de seguridad física](#medidas-de-seguridad-física)  
    - [Gestión del cableado](#gestión-del-cableado)  
    - [Infraestructura eléctrica](#infraestructura-eléctrica)  
    - [Prevención de riesgos laborales](#prevención-de-riesgos-laborales)  
    - [Sostenibilidad](#sostenibilidad)

---

## Introducción

Este proyecto transversal tiene como objetivo integrar los conocimientos adquiridos a lo largo del ciclo formativo ASIX, aplicándolos de manera práctica en el diseño e implementación de una infraestructura tecnológica realista y funcional.

---

## Descripción del proyecto

**InnovateTech** es una empresa dedicada a la creación y distribución de contenido digital. Como parte de su compromiso con la innovación tecnológica y la sostenibilidad, solicita el diseño e implementación de un **Centro de Procesamiento de Datos (CPD)** eficiente, seguro y escalable, basado en una arquitectura híbrida (infraestructura física + nube).

---

## Objetivos del proyecto

- Diseñar e implantar una infraestructura tecnológica de CPD eficiente, segura y sostenible.  
- Implementar una arquitectura de sistemas y comunicaciones robusta.  
- Garantizar la calidad del servicio de transmisión de audio y vídeo.  
- Proteger los datos según normativas internacionales.  
- Optimizar el uso de recursos y minimizar el impacto ambiental.  
- Calcular la huella ecológica.  
- Documentar el proyecto en formato Markdown y publicarlo en GitHub.  

---

## Tarea a realizar

### Definición de la arquitectura del CPD sostenible

El CPD debe garantizar alta disponibilidad, eficiencia energética y criterios de sostenibilidad. Su diseño debe considerar:

- Ubicación física estratégica  
- Eficiencia operativa  
- Seguridad física y lógica  
- Sistemas de climatización de bajo impacto ambiental  
- Alimentación eléctrica redundante  
- Integración híbrida con servicios en la nube (AWS)  

---

## Propuesta de CPD

### Ubicación física del CPD

El CPD estará ubicado en la planta baja de una nave industrial diseñada específicamente para alojar esta infraestructura. La sala principal estará en el centro del edificio, sin contacto directo con fachadas exteriores, lo que:

- Minimiza el impacto térmico  
- Optimiza la seguridad física  
- Mejora la eficiencia operativa en cableado, energía y mantenimiento  

En una zona técnica exterior se instalarán:

- Sistemas HVAC de alta eficiencia  
- Generadores eléctricos de emergencia  
- Bancos de baterías y SAIs con certificación 80 PLUS Platinum y modo ECO  

---

### Introducción y definición de la empresa

**InnovateTech** es una empresa tecnológica con sede en España, especializada en la distribución de contenido multimedia (audio y vídeo) bajo demanda y en streaming en directo. Cuenta con más de 5 millones de usuarios en Europa, y durante eventos especiales alcanza entre 500.000 y 1.000.000 de usuarios concurrentes.

---

### Objetivo del proyecto

Diseñar e implantar una infraestructura tecnológica eficiente, sostenible y escalable que permita mantener un servicio de alta disponibilidad y rendimiento ante una demanda creciente.

---

### Justificación de la arquitectura elegida

#### Arquitectura híbrida distribuida

- **Nube (AWS):** streaming, transcodificación, CDN, balanceo global  
- **CPDs propios (Tier 2):** bases de datos, autenticación, backups, monitorización  

---

### Distribución física y técnica

#### Tabla resumen de CPDs

| CPD              | Ubicación   | Tier   | Racks | Función principal                                 |
|------------------|-------------|--------|--------|---------------------------------------------------|
| CPD Central      | Madrid      | Tier 2 | 6      | Centro de control, operaciones internas, enlace AWS |
| CPD Redundante   | Barcelona   | Tier 2 | 4      | Recuperación ante desastres, almacenamiento replicado |
| CPD Backup       | Valencia    | Tier 2 | 2      | Backup offline, nodo frío, continuidad operativa     |

---

### Sistemas de climatización

- Aire acondicionado InRow (20–24°C, 45–55% humedad relativa)  
- Free cooling indirecto usando aire exterior  
- Redundancia N+1 en todos los equipos  
- Filtros HEPA para aire limpio  
- Monitorización ambiental continua (temperatura, humedad, CO₂, partículas)

---

### Medidas de seguridad física

- Fachada neutra y sin señalización  
- Accesos sin ventanas y control biométrico + RFID  
- Cámaras de videovigilancia discretas  
- Registro de accesos y salidas  
- Accesos técnicos en zonas no visibles desde el exterior  

---

### Gestión del cableado

- Separación física entre alimentación y datos  
- Código de colores para identificación rápida  
- Patch panels Cat6A blindados  
- Cableado bajo suelo técnico elevado  
- Facilitación del mantenimiento sin afectar operaciones

---

### Infraestructura eléctrica

- Alimentación redundante de doble línea eléctrica  
- SAIs online de doble conversión con autonomía mínima de 30 minutos  
- Baterías modulares y generadores automáticos  
- Monitorización energética continua  

---

### Prevención de riesgos laborales

- Formación continua en PRL  
- Señalización clara y equipos de protección individual  
- Mantenimiento preventivo planificado  
- Protocolos de evacuación y primeros auxilios  

---

### Sostenibilidad

- Equipos con certificación ENERGY STAR y 80 PLUS Platinum  
- Uso de energía verde y monitorización energética en tiempo real  
- Diseño que minimiza la longitud de cableado  
- Apagado automático de equipos en baja carga  
- Refrigeración pasiva y política de renovación sostenible  

---
