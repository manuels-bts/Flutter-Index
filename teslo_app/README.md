# Teslo App
### Flutter - Authenticated CRUD App - TesloShop

**Autenticación mediante JWT (Json Web Tokens)**
- Realizar el **POST** **HTTP**
- Obtener las **credenciales** del usuario
- Manejo de **errores** personalizados
- Manejo del estado del **formulario con Riverpod**
- Comunicación entre **providers**

A lo largo del proyecto se trabaja con:

- Cámara
- Tokens de acceso
- **CRUD** (Create Read Update Delete) Rest API Endpoints
- **Riverpod**
- **GoRouter**

Protección de rutas utilizando **Go_Router** + **Riverpod**:

- Proteger rutas
- Redireccionar
- Actualizar instancia del **GoRouter** cuando hay cambios en el estado
- Colocar **listeners** de GoRouter
- Change notifier
- **Preferencias** de usuario
- Almacenar **token** de acceso de forma **permanente**

Pantalla de **Productos** (Home):

- Login con el **boton done** del teclado
- **Masonry** ListView
- Productos
  - **Entidad**
  - **Datasources**
  - **Repositorios**
- Riverpod
  - **Provider**
  - **StateNotifierProvider**

**Creación y mantenimiento** de productos:
- Formularios
- Segmentos de botones
- **Selectores**
- **Posteos**
  - Path
  - Post
- Retroalimentación de **sucesos**
- Manejo de errores
- **Inputs** personalizados

**Cámara, Galeria y Carga de Archivos**
- **Patrón adaptador** sobre el paquete de cámara
- POST Form **Multipart**
- Mostrar imágenes como **archivos**
- Multiples cargas **simultáneas**
- Postman - Pruebas de API
- **Actualizar** **estado** del formulario
  

## Backend
- [Documentación de los endpoints disponibles](http://localhost:3000/api)
- [Teslo Backend - Nest RestServer](https://github.com/manuels-bts/Flutter-Index/tree/main/backend-teslo-shop)

# Demo

**Nota:**
Antes de correr la apliacion debes montar y correr las imagenes del backend en [**Docker**](https://www.docker.com/products/docker-desktop/) y debe lucir de esta manera.

<img width="1624" alt="Docker" src="https://github.com/manuels-bts/Flutter-Index/assets/116088500/77a0235f-ffb4-4dfc-a58d-2e32b4632e28">

---

| Screen            | Demo                                                              |
| ----------------- | ------------------------------------------------------------------ |
| **Validaciones Login** | ![Login error test](https://github.com/manuels-bts/Flutter-Index/assets/116088500/7afceaf4-0f1d-4e87-89b9-e976dc686d13) |
| **Logout** | ![Logout](https://github.com/manuels-bts/Flutter-Index/assets/116088500/025f32ae-e03c-417b-a16a-dba178e56a3a)  |
| **Products Infinite Scroll** | ![prooducts infinte scroll](https://github.com/manuels-bts/Flutter-Index/assets/116088500/d3a7ac88-a215-4f83-9e26-ab88ce2c7d09)  |
| **Product Detail** | ![product detail](https://github.com/manuels-bts/Flutter-Index/assets/116088500/3ab92665-0068-4678-81a4-55c9f5b91aa8) |
| **Product Edit** | ![product edit](https://github.com/manuels-bts/Flutter-Index/assets/116088500/07809307-9667-40ce-8ba0-c17d1697e3d7) |
| **New Product** | ![new product](https://github.com/manuels-bts/Flutter-Index/assets/116088500/4eba038e-43b4-4cdf-bbbf-e818fc98a513) |
| **Load images** | ![load images](https://github.com/manuels-bts/Flutter-Index/assets/116088500/4c4c83ef-f227-411f-80d4-94c9e9c7b35e) |
| **Form Validations** | ![validations form](https://github.com/manuels-bts/Flutter-Index/assets/116088500/6028c1dc-7821-4cc4-b36a-515a197dcbeb) |
