# Automatización de pruebas web con Cypress 🚀

El fin de este repositorio es exponer la funcionalidad de la API de Cypress para pruebas de e2e (end-to-end) en aplicaciones web. Podremos ver cómo realizar acciones en diferentes elementos de la página, como llenar formularios 📋, hacer click en botones 🔘, validar que ciertos elementos estén presentes ✅, cómo obtener el texto de un elemento 📝, encontrar elementos por su ID, clase, nombre, etc.

Se utilizará la página [demoqa.com](https://demoqa.com) para realizar las pruebas, la cual es una página de demostración de pruebas de software, donde podremos encontrar diferentes elementos y formularios para realizar pruebas.

## Introducción 🌟

Cypress es una herramienta de pruebas de front-end que permite escribir pruebas de manera eficiente y efectiva para aplicaciones web. A diferencia de otras herramientas de pruebas, Cypress está diseñado para ser fácil de usar y entender, incluso para principiantes. Ideal para pruebas tanto de UI como de integración, Cypress ofrece una experiencia de prueba sin igual con su ejecución en tiempo real y soporte de depuración. 🚀

Cypress utiliza el motor de pruebas de JavaScript Mocha y el framework de aserciones Chai, ofreciendo una experiencia de prueba integrada y amigable. Además, Cypress es compatible con la mayoría de los navegadores web modernos, incluyendo Chrome, Firefox, Edge y Electron. 🌐

## Requisitos 📋

- [Node.js](https://nodejs.org/en/) 🌐

## Instalación 🛠️

1. Iniciar un proyecto de Node.js:
   ```bash
   npm init -y
   ```
2. Instalar Cypress:
   ```bash
   npm install cypress --save-dev
   ```
   Puedes seguir la guía de instalación de Cypress [aquí](https://docs.cypress.io/guides/getting-started/installing-cypress). 📚

## Configuración ⚙️

Para crear un proyecto de automatización con Cypress, se debe ejecutar el siguiente comando:
```bash
npx cypress open
```
Este comando abrirá la interfaz de usuario de Cypress, donde se podrá crear un nuevo proyecto o abrir uno existente. 🖥️

Puedes encontrar más información sobre la configuración de Cypress [aquí](https://docs.cypress.io/guides/getting-started/opening-the-app). 📘

En este proyecto se implementará el tipo de testing End-to-End (e2e), por lo tanto, la configuración que se seguirá para el proyecto la podemos encontrar [aquí](https://docs.cypress.io/guides/end-to-end-testing/writing-your-first-end-to-end-test). 🔍

