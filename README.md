Esta guia tiene 2 idiomas disponibles

- **español**

- **ingles**

## Guia en español

# Introduccion

## ¿Que es este repositorio?

Esto es un repositiorio personal, Aunque tambien esta pensado para ser usado por otros, Por eso es publico

Aqui se guardaran videos para que los puedas usar de fondo en tus paginas web

---

## ¿Como acceder a los videos?

**primer paso:**

Aunque se le puede dar otros usos estan hechos para tus paginas

**Enseñare 2 metodos para hacer mas llamativas tus paginas**

- **para el BG de tus paginas**

- **Para solo añadirlos como video cualquiera**

## 1. Video para el BG de tus paginas

Primero es de tener en cuenta la URL necesaria, Primero copie la URL `https://ovi11-dev.github.io/videos/video_name.mp4`

**Al final de esta seccion se mostraran rapidamente todos los videos disponibles actualmente**

Ahora en su pagina web coloque una etiqueta video

---

```HTML

<div class="container">

<video autoplay muted loop class="v"> 

      <source src="https://Ovi11-dev.github.io/videos/nature.hd.mp4" type="video/mp4"> 

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

```

<video height="50" width="50" controls>

<source src="https://Ovi11-dev.github.io/videos/nature.hd.mp4" type="video/mp4">

tu navegador no soporta videos mp4

 </video>


```

**¡y listo ya tendras tu video para tu web!**

---

## Lista de videos disponibles en el repositorio

- **nature.hd.mp4 (video de naturaleza)** 

- **nature.two.hd.mp4 (video de  naturelaza 2)**

- **bike.waves.hd.mp4 (video de olas de una playa)**

> el texto encerrado en () NO forma parte del nombre del archivo, es una descripcion breve


---
