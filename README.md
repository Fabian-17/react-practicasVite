# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


# Aplicación de Contador Simple con React y Vite

Esta es una aplicación simple de contador creada con React y Vite. Este README proporciona información básica sobre cómo configurar, ejecutar y desarrollar esta aplicación.

## Requisitos previos

Asegúrate de tener Node.js y npm instalados en tu sistema. Puedes descargarlos desde (https://nodejs.org/).

## Instrucciones de configuración

1. Clona este repositorio en tu máquina local o descarga el código fuente.

```bash
git clone https://github.com/Fabian-17/react-practicasVite.git
```
2. Instala las dependencias del proyecto.
```bash
npm install
```
## Cómo ejecutar la aplicación
Una vez que hayas configurado el proyecto, puedes ejecutarlo de la siguiente manera:
```bash
npm run dev
```
Esto iniciará un servidor de desarrollo en el puerto 5173 y abrirá automáticamente la aplicación de contador en tu navegador predeterminado. La aplicación te permitirá aumentar y disminuir el contador, y verá los cambios en tiempo real.

## Cómo construir la aplicación para producción
Si deseas compilar la aplicación para producción, puedes usar el siguiente comando:
```bash
cd dist
```
Para entrar en la carpeta donde esta el proyecto.
Y luego:
```bash
npm run build
```
Esto generará una versión optimizada de la aplicación en el directorio `dist`.