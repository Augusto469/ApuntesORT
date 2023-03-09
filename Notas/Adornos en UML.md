Al representar una clase en UML podemos utilizar distintos adornos:

- + (Público): quiere decir que el atributo o método puede ser utilizado por estructuras fuera de la clase.
- - (Privado): sólo puede ser utilizado por la clase en la que está contenido.
- \# (Protegido): el elemento es usado tanto por la clase como por sus subclases.
- ~ (Package): #sinTerminar este todavía no lo vimos, así que queda pendiente jeje.
- Atributo subrayado: se le llama _atributo de clase_, sirve como atributo global, por ejemplo, la clase Math de Java define las constantes E y Pi como atributos de clase.
- Método subrayado: se le llama _método de clase_ y sirve para modificar los atributos de clase, por ejemplo:

>[!example]
>```java
>static Socio(){
>	numSocio = 0; // atributo de clase
>}
>
>public Socio(){
>	// código de prueba
>}
>```

En este caso el atributo de clase es inicializado por el constructor estático (en Java las variables static son atributos de clase) y el resto de datos son inicializados en el constructor público.

El método de clase se invoca como `objeto.metodo()`.