 Proyecto eCommerce Gamer: Descripción y Configuración

Este es un eCommerce de productos gamers, diseñado para ser rápido, eficiente y fácil de mantener. El backend se basa en Node.js y Express, con base de datos MongoDB administrada a través de Mongoose. El frontend se construyó usando React y Vite, ofreciendo una experiencia de usuario moderna y dinámica.  



 Características Principales

 Frontend:
- SPA (Single Page Application): Navegación sin recarga completa de la página.
- Carrito de compras: Gestión de productos seleccionados, con persistencia usando localStorage.
- Página de detalles del producto: Información detallada de cada producto.
- Filtros y búsqueda: Permite a los usuarios buscar productos por nombre o categorías.
- Interfaz adaptable: Optimizada para dispositivos móviles, tablets y desktops.

 Backend:
- API RESTful: Comunicación fluida con el frontend.
- Gestión de productos: Creación, edición, eliminación y consulta de productos.
- Carga de imágenes: Gestión de imágenes mediante Multer.
- Encriptación de datos sensibles: Contraseñas o datos confidenciales cifrados usando bcrypt.
- Conexión a MongoDB: Base de datos escalable y eficiente para gestionar productos y usuarios.



 Instrucciones para Configurar el Proyecto

 Requisitos previos:
- Node.js (versión LTS recomendada).
- MongoDB instalado localmente o acceso a una instancia remota.
- Git (opcional, para clonar el repositorio).
- Un gestor de paquetes: npm o yarn.

 Configuración del Backend:
1. Clonar el repositorio:
   
   git clone <url-del-repositorio>
   cd nombre-del-proyecto
   

2. Instalar dependencias:
   
   npm install
   

3. Configurar las variables de entorno:
   - Crear un archivo .env en la raíz del proyecto.
   - Incluir las siguientes variables (modificarlas según sea necesario):
     env
     PORT=5000
     MONGO_URI=mongodb+srv://<usuario>:<contraseña>@cluster.mongodb.net/<nombre_base_de_datos>
     

4. Iniciar el servidor:
   
   npm start
   

 Configuración del Frontend:
1. Entrar al directorio del frontend (si está en un subdirectorio):
   
   cd frontend
   

2. Instalar dependencias:
   
   npm install
   

3. Iniciar el entorno de desarrollo:
   
   npm run dev
   

4. Acceder a la aplicación en el navegador en http://localhost:3000.



 Dependencias Clave
 Backend:
- bcrypt: Para cifrado de datos sensibles como contraseñas.
- cors: Permite manejar solicitudes CORS entre el frontend y backend.
- dotenv: Manejo seguro de variables de entorno.
- express: Framework principal para crear el servidor y definir rutas.
- mongoose: ODM para interactuar con MongoDB.
- multer: Middleware para la carga de archivos (imágenes de productos).

 Frontend:
- React: Para construir la interfaz de usuario.
- Vite: Herramienta rápida para el desarrollo y construcción del proyecto.
