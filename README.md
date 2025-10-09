# RoomsyDevs – Proyecto ABP con WordPress

## Integrantes

- **Aguirre Griselda Leonor**
- **Alonzo Maria Agustina**
- **Bentivoglio Martín Ignacio** 
- **Lorenzati María Florencia**
- **Sofia Desiree Martinez**

## Descripción del Proyecto

Este repositorio forma parte del Sprint 0 del Proyecto ABP del equipo RoomsyDevs, para la asignatura Sistema de Gestión de Contenidos . El objetivo es preparar el entorno de desarrollo, organizar la documentación técnica y definir la estructura inicial del sitio web profesional utilizando WordPress.


## Descripción breve del sitio

RoomsyDevs es un sitio web profesional desarrollado en WordPress como portfolio grupal, donde se presentan los integrantes del equipo, sus perfiles, tecnologías aplicadas y experiencias laborales. 
El sitio refleja una identidad visual compartida y una estructura funcional pensada para mostrar el trabajo técnico de cada miembro.


## Organización del Equipo

En esta primera instancia de acercamiento y afianzamiento del proyecto, no se definieron roles individuales específicos, ya que cada integrante realizó la instalación del entorno de forma local y autónoma.

Las tareas iniciales, como la redacción del `README.md` y la documentación en la Wiki, fueron abordadas de manera colaborativa, priorizando la participación equitativa y el consenso grupal.

> La asignación formal de roles se definirá en los próximos sprints y será documentada en la Wiki del repositorio.

## Evolución del entorno técnico

Este proyecto se desarrolla en entorno local utilizando **XAMPP** (Apache, MySQL, PHP) y **WordPress** como CMS. La base de datos se gestiona con **phpMyAdmin**, y el código se documenta y versiona en **GitHub**.

### Sprint 0 – Trabajo en entorno local

Pasos de instalación:
1. Instalar XAMPP y activar Apache/MySQL.  
2. Crear la base de datos `bdroomsydevs` en `http://localhost/phpmyadmin`.  
3. Descargar WordPress desde el sitio oficial y ubicarlo en `C:\xampp\htdocs\roomsydevs`.  
4. Acceder a `http://localhost/roomsydevs` y completar el asistente de instalación.  
5. Configurar:
   - Título del sitio: RoomsyDevs  
   - Subtítulo: Portfolio profesional  
   - Usuario administrador con contraseña segura (documentada internamente).

> Las evidencias individuales de instalación fueron subidas por cada integrante a la sección **Wiki** del repositorio.

Estructura prevista del sitio:
- Menú principal: Inicio, Presentacion, Integrantes, Tecnologías y Contacto.

### Sprint 1 – Migración a entorno de producción - `https://roomsydevs.site/`
- Contratación de hosting en Hostinger con dominio .site
- Instalación limpia de WordPress en servidor
- Instalación del tema Astra y del plugin Elementor para diseño visual
- Instalación de plugins complementarios:
   - Simple History (registro de actividad por usuario)
   - Duplicate Page (replicación de estructura de CV)
- Creación de usuarios individuales con rol de administrador
- Validación de acceso, edición y publicación por cada integrante
- Definición de páginas principales: Inicio, Presentación, Integrantes, Tecnologías, Experiencia laboral y Contacto.
- Integración de páginas individuales en el submenú “Integrantes”
- Creación de páginas de CV personal desde cada usuario
- Subida de evidencias individuales de instalación y edición
- Respeto por la estética grupal y branding de RoomsyDevs

Próximas iteraciones: Se prevé la incorporación de funcionalidades adicionales como formularios personalizados de contactos y mejoras en accesibilidad.

### Sprint 2 – Funcionalidades agregadas

- Página de Tecnologías: se añadieron las tecnologías con descripción breve de cada una, y se incorporó el botón “Saber más” en cada bloque para enlazar a su página específica.

- Menú Tecnologías (Navegación): se creó una lista desplegable con cada tecnología como subelemento; al hacer clic, lleva a su página correspondiente. Cada integrante añadió las páginas que le tocaron como subelemento.

- Páginas explicativas de cada tecnología: se creó una página individual por cada tecnología listada en el menú.

- Página de Contacto: creación de formulario con Contact Form 7, almacenamiento de entradas con Flamingo y asociación a correo electrónico, verificación de recepción de entradas. Mapa de google maps de la ciudad de Cordoba.

- Blog de Experiencia Laboral: redacción de entradas de blog, creación de categoría “Experiencia”, y creación/ asignación de etiquetas por tecnología para optimizar navegación y organización interna.

- Tienda WooCommerce: creación de tienda con 3 productos/servicios, precios e imágenes; enlaces desde la sección “Servicios que ofrecemos en RoomsyDevs” del Home; creación de cupón de descuento y aviso destacado en la tienda. Servicios:

Desarrollo de Software

Desarrollo UX

Arquitectura de Sistemas

Branding y Wireframes

- Testeo general del sitio: verificación de idioma, redacción, enlaces internos y externos, errores visuales o técnicos, coherencia general del contenido y diseño responsive.