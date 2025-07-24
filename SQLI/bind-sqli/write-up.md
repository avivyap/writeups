Esta es la informacion que nos daban antes de realizar el laboratorio

![Descripción de la imagen](descripcion.png)

Asi que una vez que lei la descripcion me puse manos a la obra

Para empezar lo que hice fue mirar un poco la pagina, ver si tenia algun campo vulnerable en el apartado de las categorias, pero vi que no tenia nada (aunque realmente ya se sabia por que en la descripcion del laboratorio nos indicaban que el campo vulnerable era la cookie de sesion)

Asi que una vez probado eso, capture el trafico con burpsuite y empece a probar cosas

![2](2.png)


Estuve probando varias cosas como ' or 1=1 lo cual me devolvia un 200 de codigo de estado pero al hacer un ' or 2=1 tambien me devolvia un 200 de codigo de estado, asi que empece a probar sentencias basandose en el tiempo de espera de la pagina para ver si me las pillaba bien

![3].(3.png)




