# Mi primer README

## Mi protafolio peronal
### INDICE
- [Como ejecutar](#como-ejecutar)
- [Sobre el codigo](#sobre-el-codigo)
- [Cambios](#cambios-proximos)


En este archivo presento mi primer **PORTAFOLIO PERSONAL**. En este repositorio se concentra:
 - Un archivo **index.html** 
 - Una carpeta **img** 
    >En donde se concentra la imagen del fondo **fondo.jpg** y lam imagen del dueño del repositorio el cual es: *Reynathan Sanchez Zamora*.

    ## Como ejecutar

    Este archivo se ejecutara al dar *clic* en el archivo **index.html** lo que te permitira ver un *preview* de mi *Portafolio personal*, mostrando un acercado hacia mi persona, mi trabajo y mi formacion, ademas, de contener una foto.

    ## Sobre el codigo

    Nada fuera lo normal en lo que cabe a una pagina web sencilla, en posteriores clases se le dara una mejor presentacion, lo mas rescatable es:
    ```
    <div>
                    <label for="message">Mensaje</label>
                    <textarea type="message" id="message" name="message" row="4" required></textarea>
                </div>
    ```
    en la cual añadimos un mesaje a nuestro form, cosa que no había tenido el gusto de observar, ademas de que genera un mensaje mas grande o corto segun lo requiera.
    
    ## Cambios proximos

    Lo mas reciente que se le agregara seran cambios esteticos a las diferentes areas:
    - ### Header 
    ```
        <header>
        <!--IMAGE-->
       <center> <img src="img/me.jpg" width="500" alt="soy yo"></center>
        <h1 style="text-align: center; font-style: inherit;">Sanchez Zamora Reynathan</h1>
        <p style="text-align: center;">Estudiante de Ingeniería en Sistemas  | Deportes | CYBERSEGURIDAD </p>
    </header>
    ```	 
    >Se le añadira un formato mas completo a la cabecera asi como un diseño aun mas presentable

    - ### form
    ```
        <form>
                <div>
                    <label for="name">Nombre</label>
                    <input type="text" id="name" name="nombre" required>
                </div>
                <br> <!--mala practica usa css-->
                <div>
                    <label for="email">Correo electronico</label>
                    <input type="email" id="email" name="correo" required>
                </div>
                <br>
                <div>
                    <label for="message">Mensaje</label>
                    <textarea type="message" id="message" name="message" row="4" required></textarea>
                </div>
                <br>
                <button type="submit">Enviar</button>
            </form>
    ```
    > se dara un formato mas solido a la parte de los botones asi como a las del formulario
