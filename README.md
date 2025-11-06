# 🚘 Proyecto Vehículos - Front - Main

Este es el **frontend** del proyecto de vehículos.  
El **backend** con el cual se conecta es:  
👉 **[https://github.com/salacho00/backend--vehiculos.git](https://github.com/salacho00/backend--vehiculos.git)**

En el frontend veremos la aplicación web donde podremos usar los métodos **CRUD** de una forma más cómoda, desarrollada con **React.js**.

---

## ⚙️ Requisitos y extensiones necesarias

Para ejecutar el proyecto correctamente necesitas tener instalado:

- **Visual Studio Code**
- **Node.js** (incluye npm)
- Las **extensiones necesarias** para trabajar con React y JavaScript  

<img width="375" height="98" alt="Captura de pantalla 2025-11-06 135935" src="https://github.com/user-attachments/assets/c3c92994-5069-4e51-8127-6885e27cb8b7" />
<img width="371" height="90" alt="Captura de pantalla 2025-11-06 135953" src="https://github.com/user-attachments/assets/a8ba92dd-f9b1-42a4-9411-a9a9ea00b363" />

---

## 🧱 Estructura del proyecto

El proyecto frontend está organizado de la siguiente forma:

```text
src/
├── components/
│   ├── AlertMessage.js   # Manejador centralizado de alertas
│   ├── ItemForm.jsx      # Formulario para crear/editar ítems
│   ├── ItemList.jsx      # Lista dinámica de ítems (vehículos/motos)
│   └── ItemModal.jsx     # Modal que contiene el formulario
│
├── App.jsx               # Componente principal con tabs para Vehículos y Motos
├── main.jsx              # Punto de entrada de la aplicación
└── index.css             # Estilos globales

```
---

## 🚀 Ejecución del proyecto

Antes de iniciar el frontend, asegúrate de tener **Spring Boot** corriendo en el backend.  
Si no sabes cómo hacerlo, está detallado en el README del backend:  
👉 **[https://github.com/salacho00/backend--vehiculos.git](https://github.com/salacho00/backend--vehiculos.git)**

---

### 🔹 Pasos para ejecutar

1. Abre **Visual Studio Code**.  
2. Usa **Ctrl + O** para abrir la carpeta del proyecto (**VEHICULOS-FRONT-MAIN**).  
3. Presiona **Ctrl + Shift + X** para abrir las extensiones y descarga las necesarias.  
4. Abre la terminal con **Ctrl + Ñ** o desde la barra superior:  
   `Terminal → New Terminal`.  

<img width="779" height="486" alt="Captura de pantalla 2025-11-06 142137" src="https://github.com/user-attachments/assets/64451eb2-ce5a-4929-a553-3dcab4850054" />

---

### 🧩 Instalación de dependencias

En la terminal ejecuta: npm install
<img width="894" height="100" alt="Captura de pantalla 2025-11-06 142501" src="https://github.com/user-attachments/assets/64b13dcb-310a-484c-b87c-0714c6af2a6f" />

Cuando se haya completado, deberías ver una carpeta llamada **node_modules**.  

<img width="367" height="457" alt="Captura de pantalla 2025-11-06 142602" src="https://github.com/user-attachments/assets/c3faa6bc-cc9e-4ad4-8356-99c162d5c2a4" />

---

### ▶️ Iniciar el servidor

Para iniciar el proyecto ejecuta: npm run dev

Verás un mensaje con el link de desarrollo, por ejemplo:  
`http://localhost:5173/`

Para abrir la aplicación, coloca el mouse sobre el enlace y presiona **Ctrl + Click**.  

<img width="915" height="191" alt="Captura de pantalla 2025-11-06 142711" src="https://github.com/user-attachments/assets/211b144f-142e-47b3-83d8-9247f89ff74d" />

---

## 🌐 Visualización en la web

Una vez ingreses al link, verás la siguiente interfaz:  

<img width="1916" height="532" alt="Captura de pantalla 2025-11-06 142952" src="https://github.com/user-attachments/assets/0731e66c-2951-4e39-9385-092aab2ce869" />

La web está dividida en **dos pestañas**:
- **Vehículos**
- **Motos**

Cada sección permite:
- Ver los registros guardados.  
- Agregar nuevos.  
- Editar.  
- Eliminar.  

---

### 🚗 Agregar un vehículo

Al presionar el botón **Agregar vehículo**, aparecerá una tarjeta donde podrás ingresar los datos:
<img width="891" height="662" alt="Captura de pantalla 2025-11-06 143342" src="https://github.com/user-attachments/assets/f7cc4376-bbb6-459c-bd44-da4943cf1936" />

Un ejemplo podria ser: 
- **Marca:** Lamborghini  
- **Modelo:** Huracán  
- **Año:** 2026  
- **Imagen:** (subir imagen del carro)


<img width="620" height="550" alt="Captura de pantalla 2025-11-06 143737" src="https://github.com/user-attachments/assets/a61eeefd-99cc-4aa4-a419-c829dae8bd1d" />

Luego, presiona **Guardar** y verás un mensaje de confirmación.  

<img width="636" height="418" alt="Captura de pantalla 2025-11-06 143813" src="https://github.com/user-attachments/assets/cba33d8d-24be-407a-b80b-9d278333215c" />

---

### 🧾 Visualización de datos

Una vez guardado, el nuevo vehículo aparecerá inmediatamente en la lista con su imagen.  
Podrás:
- **Editar:** vuelve a abrir el formulario para actualizar los datos.  
- **Eliminar:** borra el registro y desaparece de la lista.  


<img width="1865" height="770" alt="Captura de pantalla 2025-11-06 143914" src="https://github.com/user-attachments/assets/2c402a4a-d0fc-4731-b5e9-377392c6b729" />

---

## 🏍️ Gestión de Motos

El funcionamiento es exactamente igual al de los vehículos.  

Solo debes ir a la pestaña **Motos**, y la página mostrará los registros correspondientes a las motos.  
Al presionar **Agregar moto**, se mostrará el mismo formulario con los campos:

- Marca  
- Modelo  
- Año  
- Imagen

un ejemplo con los datos ya añadidos: 
<img width="762" height="607" alt="Captura de pantalla 2025-11-06 144439" src="https://github.com/user-attachments/assets/bf423dba-e519-47e3-ae68-6ba2b54098ed" />

 Y se vera de esta forma en la interfaz: 
 <img width="1802" height="758" alt="Captura de pantalla 2025-11-06 144510" src="https://github.com/user-attachments/assets/ae3c9c6a-d3d2-4cfb-a7f5-8e5a4fa90872" />




---

## 👨‍💻 Autor

**README desarrollado por Juan Pablo Salazar**  
Proyecto creado con fines de **aprendizaje y desarrollo personal**.
