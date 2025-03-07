
Plataforma de Ventas Ecommerce es una solución integral para la compra y venta de productos en línea. Ofrecemos una experiencia de usuario optimizada con una amplia selección de artículos tecnológicos, también incluimos electrodomésticos y artículos para el hogar. Nuestro objetivo es brindar a los clientes acceso a productos de alta calidad al mejor precio, con un proceso de compra eficiente y seguro

Inicialmente se observa la vista del login donde de acuerdo al perfil del usuario puede acceder con sus credenciales 
![image](https://github.com/user-attachments/assets/7eca75aa-812e-4cdb-b9cc-967b26a38dd7)

Se observa el diseño de la maqueta cumple con los requerimientos que se solicitaron. Se puede observar el módulo Dashboard donde muestra el total de ingresos, las ventas realizadas y los productos vendidos como se aprecia en la imagen
![image](https://github.com/user-attachments/assets/ec915a40-6bea-43d9-9a2c-b0eaed2ab230)

Luego se selecciona el módulo de Productos con algunos de ellos ya registrados en base de datos sql server y se reflejan en la vista como se aprecia en la imagen

![image](https://github.com/user-attachments/assets/ae95f925-f470-4a13-bcde-72982d6bc140)

Luego se puede seleccionar el módulo de Ventas donde se puede efectuar una compra como se aprecia en la imagen

![image](https://github.com/user-attachments/assets/71f7dd4a-a7e0-4646-8b13-c6a556a5c2ef)

Se puede seleccionar el módulo de historial de ventas donde se puede ver el detalle de la venta realizada como se aprecia en las imágenes

![image](https://github.com/user-attachments/assets/35e0324d-4296-4377-ae4c-4f435b900a2c)

![image](https://github.com/user-attachments/assets/35b5a9b4-8514-4dc7-873a-a9de3730d5b9)

También cuenta con un módulo de reportes donde se puede realizar un reporte filtrando por fecha de cuando fue realizada la venta y exportar a excel 

![image](https://github.com/user-attachments/assets/2af0287f-ced6-4d3f-b416-8469649d33d0)

Modo en que se realizó la plataforma Ecommerce: la maquetación fue realizada por Angular versión 15, en este caso ya está funcionando ya que está conectada a base de datos sql server y el backend realizado en la plataforma .Net-Core

La plataforma "Sistema de ventas Ecommerce" fue realizado bajo las especificaciones planteadas cuya maquetación cumpliera con lo solicitado, que era crear un proyecto front de libre albedrio que consumiera datos de una API. en este caso yo escojí angular 15 para el frontend y poder consumir un crud de datos realizado en ASP.NET-CORE, donde expongo 4 servicios API-REST-FULL "GET", "POST","PUT" y "DELETE". La aplicación está realizada bajo una arquitectura de N-capas, empleando un patron repositorio, empleando DTOS, validaciones de datos, autommaper, interfaces e inyección de dependencias, con buenas prácticas y principios solid.


Tarea: Asignación No. 3 Desarrollo de un validador de formularios dinámico del lado del cliente, caso Registro de nuevo Usuario del Sistema

Como se aprecia en la imagen los campos validan su obligatoriedad

![image](https://github.com/user-attachments/assets/528c2e6d-4ee1-4684-b9a8-13ac1f68319b)

En este caso también valida que el formato del correo electrónico sea el formato correcto como se ve en la imagen

![image](https://github.com/user-attachments/assets/cdccb09f-a332-40d9-aeb9-b97d2a4f5e7c)

Se ingresan las credenciales equivocadas y arroja el mensaje de alerta notificando que no se encontraron coincidencias

![image](https://github.com/user-attachments/assets/3e688369-8aa7-4301-99c7-3da646b8b942)


En este caso ya se ingresa el email y contraseña correctos para poder ingresar

![image](https://github.com/user-attachments/assets/1b8be49e-93e9-4225-8fa6-2b58f0be9219)

Del mismo modo las validaciones de los campos ocurren en el módulo Agregar Usuarios, no se activa el botón guardar hasta que no se llenen los campos por completo

![image](https://github.com/user-attachments/assets/23929bcf-3db0-47cd-ac8b-50fd0b93e404)

De igual forma en el módulo "Agregar Producto"

![image](https://github.com/user-attachments/assets/a923dcee-7306-4954-a40e-ec9931cf82ee)

De igual manera con el módulo "Ventas"

![image](https://github.com/user-attachments/assets/2b7f0de5-ee15-4e99-9756-5c9e3f8d1dea)

De igual manera con el módulo de "Reportes"

![image](https://github.com/user-attachments/assets/e484d03a-c03e-4c91-affe-114a74526fa8)

Al realizar un ingreso de un usuario con rol de empleado, se llenan los datos como se muestra a continuación 

![image](https://github.com/user-attachments/assets/71e11423-c130-4ff1-a72e-836346005860)

Y se observa que se ingresa correctamente en la grilla y mostrando un mensaje de alerta exitoso como se aprecia en la imágen

![image](https://github.com/user-attachments/assets/f6485d89-f8fe-4a06-b374-4511d0d7d1ef)

Las validaciones de los campos y los mensajes de alerta del lado cliente fueron implementados utilizando Angular 14. Se usaron Reactive Forms para gestionar la validación de los inputs, incluyendo la verificación del formato del email con Validators.email. Además, se empleó Angular Material para mostrar mensajes de error y mejorar la experiencia del usuario.










