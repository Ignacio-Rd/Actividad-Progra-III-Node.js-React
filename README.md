# Actividad - Introducción a React y Node.js

## Respuestas a las pautas de entrega

### 1. ¿Para qué sirve el archivo package.json?
Es el archivo de configuración central de cualquier proyecto de Node.js. Funciona como el "manifiesto" del proyecto y sirve principalmente para:
* **Registrar metadatos:** Guarda información básica como el nombre del proyecto, versión y autor.
* **Gestionar dependencias:** Lista de forma exacta los paquetes y librerías externas que el proyecto necesita para funcionar (como `react` o `vite`). Gracias a esto, no hace falta subir la carpeta `node_modules`, ya que cualquiera puede reconstruirla ejecutando `npm install`.
* **Definir scripts:** Automatiza comandos comunes mediante alias (por ejemplo, mapear `npm run dev` para que ejecute el servidor de desarrollo de Vite).

---

### 2. ¿Qué diferencia notaron entre ejecutar un archivo directamente con Node.js y levantar el servidor de React?
* **Ejecutar con Node.js (`node App.js`):** Corre el script de JavaScript directamente sobre el entorno de ejecución de la computadora en un único paso. 
* **Levantar el servidor de React (`npm run dev`):** No solo ejecuta código, sino que monta un **servidor web de desarrollo local** activo (en segundo plano).