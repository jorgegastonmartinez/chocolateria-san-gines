## Título del Proyecto

Ecommerse Chocolatería San Gines Argentina. 


## Descripción

Este proyecto es una plataforma de ecommerce para la Chocolatería San Gines, donde los usuarios pueden explorar una lista completa de productos, filtrarlos por categorías, ver detalles individuales, y agregar productos a su carrito de compras. El sistema incluye funcionalidades como la gestión del carrito, eliminación de productos, vaciado completo del carrito, y un proceso de checkout que permite al usuario finalizar la compra y recibir un ID de orden tras un envío exitoso de los datos. Toda la información del pedido se guarda en Firebase. 


## Funcionalidades

### Visualización de todos los productos del ecommerse
- Muestra una lista completa de todos los productos de la Chocolatería San Gines.

### Filtro de categorias
- Permite filtrar los productos por su categoría.

### Detalle de productos
- Al clickear sobre uno de ellos, se enviará a una pagina de detalle del producto, donde se puede agregar la cantidad deseada de productos al carrito. Si el producto fue añadido exitosamente, se muestra un mensaje.

### CartWidget
- Si hay productos añadidos al carrito, se mostrarán con un numerito debajo del icono del carrito.En el carrito, se muestran todos los productos añadidos. Allí es posible borrar productos de forma individual, vaciar el carrito por completo y volver a la tienda para seguir cargando productos. Si en el carrito no hay productos añadidos se mostrará el mensaje “no hay productos en el carrito”.

### Finalizar compra
- Al finalizar la compra nos dirigirá a una pagina donde el usuario deberá cargar correctamente todos los datos para poder concretar la compra.

### Checkout
- Una vez finalizada la compra nos mostrará el ID de la orden de la compra, a través de un mensaje, solo si, el usuario cargó todos los datos correctamente. Se podrá obtener el ID y el formulario se enviará a firebase.


## Tecnologías

![ReactJs](https://img.shields.io/badge/ReactJs-61DAFB?style=for-the-badge&logo=react&logoColor=white) Biblioteca JavaScript para construir la interfaz de usuario.

![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white)

![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white) Para gestionar la navegación y las rutas dinámicas entre las diferentes vistas de la aplicación.

![Material UI](https://img.shields.io/badge/Material--UI-007FFF?style=for-the-badge&logo=mui&logoColor=white) Framework de componentes de interfaz de usuario para React, que proporciona componentes preconstruidos y estilos personalizados.

![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white) Para los estilos de la aplicación, creando un diseño limpio y funcional.


## Uso

- Copie la siguiente url en su navegador 
```
https://jorgegastonmartinez.github.io/chocolateria-san-gines/
```

* Utilice las categorías para filtrar la búsqueda de los productos.
* Seleccionar el producto que desee comprar.
* En el detalle se puede seleccionar cantidades. Con el button "agregar al carrito”, podrás ir agregando los productos al carrito de compras.
* Para realizar el pedido, dirigirse al carrito de compras, ubicado en la parte superior, dentro de la navbar.
* Allí podrás agregar mas productos (volviendo a la tienda) eliminar productos, vaciar carrito, ver los precios detallados, el subtotal de cada producto, el total de todos los productos agregados al carrito y finalizar la compra.
* Completar el formulario para poder realizar la compra. Cuando los datos del formulario se cargaron correctamente, se mostrará el ID de compra.
* En el siguiente link de firebase `https://console.firebase.google.com/u/1/project/e-commerse-d742e/firestore/data/~2FstoreOrders?hl=es` , se verán reflejadas las ordenes de pedidos y la tienda con todos los productos cargados.


## Comandos

1. Clonar el repositorio desde Github
```
git clone https://github.com/jorgegastonmartinez/chocolateria-san-gines.git
```

2. Navega a la carpeta del proyecto
```
cd ecommerse-react
```

3. Instalar las dependencias
```
npm install
```

4. Inicia la aplicación en modo de desarrollo
```
npm run dev
```

## Imágenes del proyecto

![Captura de pantalla 2024-01-31 a la(s) 20 27 01](https://github.com/jorgegastonmartinez/ReactJs/assets/140458867/9e715a90-94c2-442e-992a-fdc58e4f4191)

![Captura de pantalla 2024-01-31 a la(s) 20 29 38](https://github.com/jorgegastonmartinez/ReactJs/assets/140458867/0a98a6a6-1872-4d15-9a0a-8a1cdbb85f1f)

![Captura de pantalla 2024-01-31 a la(s) 20 27 36](https://github.com/jorgegastonmartinez/ReactJs/assets/140458867/f843d44c-17a1-428b-9821-ace03aebee6c)

![Captura de pantalla 2024-01-31 a la(s) 20 28 49](https://github.com/jorgegastonmartinez/ReactJs/assets/140458867/994e24ed-dd13-4602-858f-c1e29d07a73f)

![Captura de pantalla 2024-01-31 a la(s) 20 29 15](https://github.com/jorgegastonmartinez/ReactJs/assets/140458867/d085adee-83b0-4288-8795-df401fe88b6e)

![Captura de pantalla 2024-01-31 a la(s) 20 26 03](https://github.com/jorgegastonmartinez/ReactJs/assets/140458867/f0b1f653-4727-473a-bbaf-7cb0c6227687)


## Contacto

Si tienes alguna pregunta o inquietud, puedes ponerte en contacto conmigo
- Correo jgastonmartinez@gmail.com
- Github https://github.com/jorgegastonmartinez