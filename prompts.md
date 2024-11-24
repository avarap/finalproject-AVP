> Detalla en esta sección los prompts principales utilizados durante la creación del proyecto, que justifiquen el uso de asistentes de código en todas las fases del ciclo de vida del desarrollo. Esperamos un máximo de 3 por sección, principalmente los de creación inicial o  los de corrección o adición de funcionalidades que consideres más relevantes.
Puedes añadir adicionalmente la conversación completa como link o archivo adjunto si así lo consideras


## Índice

1. [Descripción general del producto](#1-descripción-general-del-producto)
2. [Arquitectura del sistema](#2-arquitectura-del-sistema)
3. [Modelo de datos](#3-modelo-de-datos)
4. [Especificación de la API](#4-especificación-de-la-api)
5. [Historias de usuario](#5-historias-de-usuario)
6. [Tickets de trabajo](#6-tickets-de-trabajo)
7. [Pull requests](#7-pull-requests)

---

## 1. Descripción general del producto

**Prompt 1:**

vamos a desarrollar una web app para llevar las finanzas personales se va a llamar whereismymoney
1. el desarrollo se va hacer en MERN
2.el github del proyecto actual es https://github.com/avarap/whereismymoney para que lo puedas consultar
3. vas a rellenar la siguiente plantilla:
## 1. Descripción general del producto

> Describe en detalle los siguientes aspectos del producto:

### **1.1. Objetivo:**
### **1.2. Características y funcionalidades principales:**
### **1.3. Diseño y experiencia de usuario:**
### **1.4. Instrucciones de instalación:**
## 2. Arquitectura del Sistema
### **2.1. Diagrama de arquitectura:**
### **2.2. Descripción de componentes principales:**
### **2.3. Descripción de alto nivel del proyecto y estructura de ficheros**
### **2.4. Infraestructura y despliegue**
### **2.5. Seguridad**
### **2.6. Tests**
---
## 3. Modelo de Datos
### **3.1. Diagrama del modelo de datos:**
### **3.2. Descripción de entidades principales:**
## 4. Especificación de la API
## 5. Historias de Usuario
> Documenta 3 de las historias de usuario principales utilizadas durante el desarrollo, teniendo en cuenta las buenas prácticas de producto al respecto.

---
## 6. Tickets de Trabajo
> Documenta 3 de los tickets de trabajo principales del desarrollo, uno de backend, uno de frontend, y uno de bases de datos. Da todo el detalle requerido para desarrollar la tarea de inicio a fin teniendo en cuenta las buenas prácticas al respecto. 

---
## 7. Pull Requests
> Documenta 3 de las Pull Requests realizadas durante la ejecución del proyecto

Te puedo dar esta información extra:

Descripción general del producto:

1.1. Objetivo: ¿Cuál es el propósito principal de la aplicación? Por ejemplo, ¿ayudar a los usuarios a rastrear sus gastos, establecer presupuestos, generar informes financieros, etc.?
>El objetivo principal es que los usuarios lleven un control de ingresos y gastos y puedan tener esa información visualmente con informes y graficos

1.2. Características y funcionalidades principales: ¿Qué funcionalidades específicas ofrecerá la aplicación? Por ejemplo, ¿registro de transacciones, categorización de gastos, alertas de presupuesto, informes gráficos, etc.?
>el usuario podrá ver sus ingresos y gastos, añadir nuevos, categorizarlos, poder fraccionar gastos con otras personas

1.3. Diseño y experiencia de usuario: ¿Existe alguna guía de estilo o prototipos de diseño que definan la apariencia y la experiencia del usuario en la aplicación?
>el look and feel de la pagina será moderno parecido a la página de airbnb, que sea profesional y fácil de usar

1.4. Instrucciones de instalación: ¿La aplicación está destinada a ser desplegada localmente por los usuarios o se ofrecerá como un servicio en línea? ¿Hay instrucciones específicas para la instalación y configuración?
>la aplicación será una web online y el usuario podrá usar google auth

Arquitectura del Sistema:
2.1. Diagrama de arquitectura: ¿Existe un diagrama que represente la arquitectura del sistema? Si no, ¿podría proporcionar una descripción general de cómo se estructuran los componentes principales?
>en la web https://github.com/avarap/whereismymoney hay un desarrollo hecho, pero no tengo un modelo de datos definido, se aceptan mejoras.

2.2. Descripción de componentes principales: ¿Cuáles son los componentes clave del sistema y cómo interactúan entre sí?
>en la web https://github.com/avarap/whereismymoney actualmente es lo que hay hecho, pero propon mejoras.

2.3. Descripción de alto nivel del proyecto y estructura de ficheros: ¿Podría proporcionar una visión general de la estructura de directorios y archivos del proyecto?
>en la web https://github.com/avarap/whereismymoney

2.4. Infraestructura y despliegue: ¿Dónde se desplegará la aplicación (por ejemplo, en un servidor específico, en la nube)? ¿Qué herramientas o servicios se utilizarán para el despliegue?
>Frontend: https://subtle-sable-83e760.netlify.app/
>Backend: https://whereismymoney.onrender.com

2.5. Seguridad: ¿Qué medidas de seguridad se implementarán para proteger los datos de los usuarios y la integridad del sistema?
>actualmente no hay ninguno, haz una propuesta

2.6. Tests: ¿Qué enfoque se seguirá para las pruebas? ¿Se utilizarán pruebas unitarias, de integración, de extremo a extremo?
>actualmente no hay ninguno, propon los tests

Modelo de Datos:
3.1. Diagrama del modelo de datos: ¿Existe un diagrama que represente las entidades y sus relaciones en la base de datos?
>no


Puedes hacerme las preguntas necesarias para completarlo antes de hacer cualquier cosa.
la plantilla devuelvela en un fichero formato Markdown.
el modelo de datos hazlo en mermaid.
al finalizar puedes generar un fichero md para descargar

**Prompt 2:**

Seguridad:
¿Deseas implementar autenticación de dos factores (2FA) además de Google Auth? 
>No
¿Qué nivel de cifrado necesitas para la base de datos y para las comunicaciones (SSL, encriptación de campos sensibles como contraseñas)?


Tests:
¿Qué frameworks de pruebas estás considerando (por ejemplo, Jest para frontend y backend, Cypress para pruebas de extremo a extremo)?
> Jest para ambos
¿Qué nivel de cobertura de pruebas buscas (por ejemplo, solo las funcionalidades críticas o todo el sistema)?
>Todo

Modelo de datos:
¿Qué campos principales tendrán las entidades como usuarios, transacciones, y categorías? ¿Hay atributos como fecha, monto, descripción, etc. que consideres imprescindibles?
>en la web https://github.com/avarap/whereismymoney

Historias de usuario:
¿Quieres incluir casos específicos como alertas personalizadas, informes exportables, o alguna otra funcionalidad no mencionada?
Registrar nuevos ingresos y gastos, editarlos y visualizarlos
categorizar los ingresos y gastos
exportar informes

**Prompt 3:**

---

## 2. Arquitectura del Sistema

### **2.1. Diagrama de arquitectura:**

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

### **2.2. Descripción de componentes principales:**

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

### **2.3. Descripción de alto nivel del proyecto y estructura de ficheros**

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

### **2.4. Infraestructura y despliegue**

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

### **2.5. Seguridad**

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

### **2.6. Tests**

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

---

### 3. Modelo de Datos

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

---

### 4. Especificación de la API

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

---

### 5. Historias de Usuario

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

---

### 6. Tickets de Trabajo

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

---

### 7. Pull Requests

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**
