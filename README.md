# 📊 Dashboard de Inventario Interactivo

Este es un sistema de gestión de inventarios dinámico que utiliza **Google Sheets** como base de datos y una interfaz moderna construida con **React, Vite y Tailwind CSS**. Permite registrar ventas, compras y visualizar métricas financieras en tiempo real.

## 🚀 Características principales

- **Conexión con Google Sheets:** Almacenamiento de datos gratuito y accesible mediante Google Apps Script.
- **Gestión de Inventario:** Creación de categorías, registro de productos con códigos únicos y control de stock.
- **Transacciones:** Registro eficiente de entradas (compras) y salidas (ventas).
- **Dashboard Visual:** Gráficos interactivos y métricas clave (Ventas, Compras, Ganancias y Gastos).
- **Base de Datos Automática:** Configuración inicial que genera las pestañas necesarias en tu hoja de cálculo con un solo clic.

## 🛠️ Tecnologías utilizadas

- **Frontend:** React.js, Vite, Tailwind CSS.
- **Backend/DB:** Google Apps Script, Google Sheets API.

## 📋 Configuración Paso a Paso

### 1. Preparación de Google Sheets

1. Crea una nueva hoja de cálculo en Google Sheets.
2. Abre **Extensiones > Apps Script**.
3. Copia el código del archivo `sg.js` (proporcionado en este proyecto) y pégalo en el editor de Apps Script.
4. Sustituye la constante del ID del documento por el ID de tu propia hoja de cálculo.
5. Haz clic en **Implementar > Nueva implementación** como "Aplicación Web" y otorga los permisos necesarios.
6. Copia la **URL de la aplicación web** generada.

### 2. Configuración del Proyecto Local

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/g0nzano/inventario.git](https://github.com/g0nzano/inventario.git)
   Abre el archivo script.js y busca la variable de la URL:
   ```

JavaScript

const URL_APP_SCRIPT = "TU_URL_AQUI";
Pega la URL que copiaste de Apps Script.

3. Inicialización
   Inicia el proyecto en tu navegador.

Ve a la sección de Configuración.

Haz clic en "Iniciar base de datos". Esto creará automáticamente las hojas necesarias en tu Google Sheets.
