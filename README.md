# AluraPlay

AluraPlay es un proyecto que simula una plataforma de streaming de videos, similar a YouTube, donde los usuarios pueden explorar diferentes videos relacionados con la programación, ciencia de datos, diseño UX, entre otros temas. Este proyecto es parte de los cursos de desarrollo web de Alura Latam.

## Características

- **Navegación Intuitiva:** La interfaz de usuario está diseñada para ser intuitiva y fácil de usar, permitiendo a los usuarios navegar a través de las diferentes secciones de contenido de manera eficiente.

- **Diversidad de Contenidos:** AluraPlay ofrece una amplia gama de videos educativos que cubren diversos temas como programación, ciencia de datos, diseño UX, y más.

- **Diseño Responsivo:** La plataforma está diseñada para ser responsiva, asegurando una experiencia de usuario óptima en dispositivos móviles y de escritorio.

## Estructura del Proyecto

El proyecto está estructurado en HTML y CSS, con una organización clara que facilita su comprensión y escalabilidad.

### Cabecera

La cabecera incluye un logo, un campo de búsqueda, y accesos directos a videos, aplicaciones, notificaciones, y el perfil del usuario.

```html
<header>
    <nav class="cabecera__container">
        <h1 class="logo__item" href="#"></h1>
        <div class="cabecera__buscar__item">
            <form action="">
                <input type="search" placeholder="Buscar" id="buscar" class="buscar__input">
                <label for="buscar" class="buscar__label"></label>
            </form>
            <a href="#" class="cabecera__audio"></a>
        </div>
        <div class="cabecera__iconos__item">
            <a href="#" class="cabecera__videos"></a>
            <a href="#" class="cabecera__apps"></a>
            <a href="#" class="cabecera__notificaciones"></a>
            <a href="#" class="cabecera__avatar"></a>
        </div>
    </nav>
</header>
Menú Lateral
El menú lateral ofrece acceso rápido a diferentes secciones como Inicio, Explorar, Shorts, Suscripciones, y más.

<aside class="menu__container">
    <ul class="menu__lista">
        <!-- Items del menú aquí -->
    </ul>
</aside>
Sección de Videos
La sección principal muestra una colección de videos que los usuarios pueden explorar.

<ul class="videos__container">
    <!-- Lista de videos aquí -->
</ul>
Pie de Página
El pie de página contiene enlaces a diferentes categorías de contenido, como Programación, Data Science, UX e Design, entre otros.

<footer class="rodapie__container">
    <!-- Secciones del pie de página aquí -->
</footer>
Tecnologías Utilizadas
HTML5
CSS3
Instalación
Para utilizar este proyecto, simplemente clona el repositorio en tu máquina local y abre el archivo index.html en tu navegador.

git clone https://github.com/pablodomingok/alura-play.git
cd alura-play
Contribuir
Si estás interesado en contribuir a este proyecto, por favor lee las directrices de contribución y envía tus pull requests.

Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.


Este README proporciona una visión general detallada del proyecto AluraPlay, incluyendo su propósito, características, estructura, tecnologías utilizadas, instrucciones de instalación, cómo contribuir, y la licencia.
