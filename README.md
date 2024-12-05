**This guide is intended to be in Spanish, use Google Translate to view it correctly.**
---

# Introduccion

## ¿Que es este repositorio?

Esto es un repositiorio personal, Aunque tambien esta pensado para ser usado por otros, Por eso es publico

Aqui se guardaran videos para que los puedas usar de fondo en tus paginas web

> [!NOTE]
> Recuerda que puedes visitar [mi sitio web](https://Ovi11-dev.github.io/VFYW/page/VFYW%20-%20page/index.html) sobre VFYW :)
---

## ¿Como acceder a los videos?

**primer paso:**

Aunque se le puede dar otros usos estan hechos para tus paginas

**Enseñare 2 metodos para hacer mas llamativas tus paginas**

- **para el BG de tus paginas**

- **Para solo añadirlos como video cualquiera**

## 1. Video para el BG de tus paginas

Primero es de tener en cuenta la URL necesaria, Primero copie la URL `https://Ovi11-dev.github.io/VFYW/videos/<video>`

**Al final de esta seccion se mostraran rapidamente todos los videos disponibles actualmente**

Ahora en su pagina web coloque una etiqueta video

---

```HTML

<div class="container">

<video autoplay muted loop class="v"> 

      <source src="https://Ovi11-dev.github.io/VFYW/videos/nature.hd.mp4" type="video/mp4"> 

Tu navegador no soporta el elemento de video.
        

</video>

</div>

```

---

**Ahora,  ejecuta este codigo CSS**

```CSS

body {
    

 margin: 0;
    
    
    
}
.container {
    
    position: relative;
    
    min-height: 100vh;
    
    
}
.v { 

    position: absolute;
    
    top: 0%;
    
    left: 0%;
    
    width: 100%;
    
    height: 100%;
    
    
    object-fit: cover;
    
}

```

---

 ¡Y listo ya tendras un video de fondo para tu pagina web!

---

## 2. Video para tus paginas

si simplemente quieres agregar un video y modificarlo despues a tu gusto

¡No te preucupes! Aqui Tienes los pasos para hacerlo


**Para esto solo necesitaras una etiqueta de video y su correspondiente URl**

como unico paso ejecuta el siguienten codigo html

```HTML

<video height="50" width="50" controls>

<source src="https://Ovi11-dev.github.io/VFYW/videos/nature.hd.mp4" type="video/mp4">

tu navegador no soporta videos mp4

 </video>


```



**¡y listo ya tendras tu video para tu web!**

---

## **Extra: ¿Como descargar?**

Para descargar un video, Es relativamente facil

Esto sera hecho en una terminal, como unico requisito, Tener a `wget` instalado.

**Sólo un comando y ya**

copia y pega el siguiente comando en tu terminal, Luego sigue las indicaciones

```bash

wget https://Ovi11-dev.github.io/VFYW/videos/<video>

```

---

**indicaciones:**

- Cambia `<video>` por el nombre del video correspondiente

- verificar la instalacion con el comando `ls` en su directorio

- tener de antemano a `wget` instalado

---


## Ejemplos

**Aqui se mostraran ejemplos de como deberia verse**

Contenido actual:

- ** 2 GIFs 👾**

- ** 1 img 🖼️**

---


### ¿Cómo deberia verse el video BG? [GIF 👾]

**ejemplo:**

![BG video ejemplo](https://Ovi11-dev.github.io/VFYW/examples/BG_video_example.gif)

---

### ¿Cómo deberia verse el video? [GIF 👾]

**ejemplo:**

![video ejemplo](https://Ovi11-dev.github.io/VFYW/examples/video_example.gif)

---

### ¿Como deberia verse lo retornado por `wget` y `ls`]? [img 🖼️]

**ejemplo: **

![comandos ejemplo](https://Ovi11-dev.github.io/VFYW/examples/wget_example.jpg)



---

## importante ‼️

**en estos ejemplos no se especifico un detalle importante**

**si estas usando el metodo de video de BG, El contenido principal aparte del video debe tener unas configuraciones extras**

Si esto no es considerado podrias tener los siguientes errores

- **Problemas con la adaptacion del tamaño del video de fondo**

- **Visualmente Nada atractivo**

- **todos los anteriores**


---

### ¿Cómo solucionar?

primero encierre su codigo principal en una etiqueta `<div></div>` 

> [!NOTE]
> Con "codigo principal" tambien se toma cuenta el `<header>` y el `<footer>` de su web. NO incluir la etiqueta `<video>` en el div

Ahora agregue una clase al elemento div, La clase y su nombre son de preferencia pero podria ponerle de nombre **layer** O **main**

Ahora si quiere un mejor ejemplo podria ver o copiar este codigo html de ejemplo

---

```HTMl

<div class="layer">

<!---- Main Content Here ----<

</div>

<div class="container">

<video autoplay muted loop>

<source src="https://Ovi11-dev.github.io/VFYW/videos/video.mp4>

Tu navegador no soporta videos mp4

</video>

</div>

```
> [!NOTE]
> Recuerda remplazar "video.mp4" con algunos de los que puedes encontrar en este repositorio

--- 

Ahora teniendo esto en cuenta, Vea o copie el siguiente codigo CSS

```CSS

.layer { 
    
    position: absolute;
    
    z-index: 1;
}

```
---

**¡Y listo! Este problema habra sido arreglado**

## Lista de vidos disponibles actualmente

- nature.hd.mp4 (video sobre naturaleza)

- nature.hd.mp4 (version mejorada de el primero pero menos hecho para repetirse en bucle)

- bike.waves.hd.mp4 (video sobre olas de una playa)

- technology.hd.mp4 (video en bucle)

- circle.neon.hd.mp4 (circulo neon en bucle)

- red.bg.hd.mp4 (video de un fondo rojo con brillitos en bucle)

- car.hd.mp4 (video de carro en hd en bucle)

- BG.neon.hd.mp4 (video en bucle para fondos)

> [!NOTE]
> Los () NO forman parte del nombre del archivo, son una descripcion rapida de su contenido

---

> [!IMPORTANT]
> Viste mi sitio de [preview de los videos actuales](https://ovi11-dev.github.io/VFYW/page/VFYW%20-%20page/preview.html)

---

