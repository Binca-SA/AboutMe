//TÍTULO DEL PROYECTO//
    Ejercicio de Figma pasado a HTML Y CSS

//DESCRIPCIÓN DEL PROYECTO//
    Crear un modelo idéntico a la propuesta en Figma, siguiendo las directrices en:
        - medidas
        - color
        - tipografía

//HERRAMIENTAS UTILIZADAS//
    - Diseño:Figma
    - Código: HTML y SCSS

//CARPETAS//
    La carpeta raíz: "FIGMA1.2" dentro de ella encontramos: 
        >css
            style.css
        >Images
            1636538605927.jpg //
        >sass
            >components //la arquitectura que conforma la página web, cada elemento, se encuentra en un archivo diferente:
                _avatar-header.scss //Foto de perfil 
                _buttons.scss //Botones del header
                _header.scss //Elementos del header como H1 y H5.
                _navigation.scss //Elementos de la navegación
            >libreria//se encuentran los mixins y variables:
                _mixins.scss
                _variables.scss//se han establecido variables para los colores, la tipografía y márgenes:
                    A continuación una explicación del uso adecuado de cada variable:
                        //COLORES//
                        $background-body:#ADAFEE; ->se utiliza para el color de fondo del site
                        $background-nav: #B6F6D0; ->se utiliza para el color de fondo de la navegación
                        //TIPOGRAFÍA//
                        $tipografia-body:'Space Grotesk', sans-serif; ->se utiliza para todo
                        //MEDIDAS//
                        $margins: 30px; ->se aplica a los margenes de los navs y tambien al tamaño de los svg del interior de los navs.
            >site//se encuentran las características generales del site
                    _site.scss

//SINTAXIS//
    -Comentarios
        Se escriben en mayúscula
        Sin espaciado entre el código y los comentarios
    -Tabulación en lugar de espacios en blanco
    -Se permiten líneas en blanco al pasar a otro selector, tema o categoría.
    -No se admiten líneas en blanco dentro de los selectores


//NOTA//
    -No ha sido necesario utilizar media query, se adapta perfectamente a dispositivo movil y desktop. 
