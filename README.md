
# Maquetación UI estilo WhatsApp 

Este proyecto consiste en la **maquetación de clone de WhatsApp Web**, desarrollada con **HTML y CSS**

La interfaz reproduce las principales secciones visuales de la aplicación:

* Un **sidebar** con la lista de chats
* Un **panel principal** con la conversación activa
* Header y footer fijos, con el área de mensajes desplazable
* **Responsive** de distintas resoluciones para la adaptabilidad de diversos dispositivos


Se buscó replicar el aspecto general de WhatsApp, adaptándolo a un **modo oscuro**, con detalles visuales propios.


## Tecnologías utilizadas

* **HTML5**
* **CSS3** (Flexbox y media queries)
* **Assets** (Imagenes y SVGs)

No se utilizaron librerías externas ni JavaScript.

---

## Estructura del proyecto

```
/index.html
/styles/main.css
/assets/
  ├─ imágenes de perfil
  ├─ íconos
  ├─ stickers
  └─ favicon
```

---

## Cómo visualizar el proyecto
1. Clonar el repositorio desde GitHub:
   ```bash
    git clone https://github.com/bySanzzz/proyecto-base-wsp.git
    cd proyecto-base-wsp
    
2. Abrir el archivo `index.html` en cualquier navegador moderno.

---
* No requiere instalación adicional.



## Decisiones de diseño y consideraciones

* Se implementó un **modo oscuro** con una paleta de colores inspirada en WhatsApp Web.
* La maquetación se realizó principalmente con **Flexbox**, permitiendo una estructura clara y adaptable.
* El área de mensajes cuenta con **scroll personalizado similar a WhatsApp**.
* Se agregó un **favicon** representativo de la aplicación.
* Los mensajes incluyen **checks de visto y no visto** como detalle visual.
* Se desarrolló un diseño **responsive con triple vista** (mobile, tablet y desktop), adaptando la disposición de los paneles según el tamaño de pantalla.

---

## Trabajo con Git

El proyecto fue desarrollado utilizando **commits frecuentes y descriptivos**, reflejando el avance progresivo del trabajo.

Los commits documentan:

* layout: implementación de diseño responsive con triple vista

* style: actualización visual de la aplicación y agregado de checks de mensajes

* update: agregado de mensajes, stickers y ajustes de textos del chat

* style: implementación de modo oscuro y ajustes en botones

* update: ajustes de imágenes y textos

Este enfoque permitió mantener un historial claro y ordenado del desarrollo.

