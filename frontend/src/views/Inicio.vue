<template>
  <main>
    <iframe
      width="100%"
      height="550"
      src="https://www.youtube.com/embed/k5rZk-qC0JM"
      title="YouTube video player"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen>
    </iframe>
    <div class="sub">
        <iframe height="20"></iframe>
        <h2>Senarautas serie web</h2>
        <iframe height="30"></iframe>
    </div>

    <div class="contenedor-serie">
      <div class="am">
        <a href="frontend\src\views\quienessomos.vue" title="Quienes somos"><b-img
          src="https://electronics-aid.com/wp-content/uploads/2018/06/QUIENES-SOMOS.png"
          height="300"
          width="300"
          fluid
          alt="somos"
        ></b-img></a>
        <br><br><a class="boton" href="#">Quiénes Somos</a><br><br>
        <!-- <a href="#" id="un">Quienes somos</a> -->
      </div>
      <div class="am">
        <iframe
          src="https://calendar.google.com/calendar/embed?height=253&wkst=1&bgcolor=%23ffffff&ctz=America%2FBogota&src=ZXMtNDE5LmNvI2hvbGlkYXlAZ3JvdXAudi5jYWxlbmRhci5nb29nbGUuY29t&color=%230B8043"
          style="border: solid 1px #777"
          width="250"
          height="240"
          frameborder="0"
          scrolling="no"
        ></iframe>
        <br><br><a class="boton" href="#">Calendario</a><br><br>
        <!-- <a href="#" id="cua">Calendario</a> -->
      </div>
      <div class="am">
        <a href="frontend\src\views\trasbambalinas.vue" title="Tras Bambalinas"><b-img
          src="https://image.flaticon.com/icons/png/512/931/931216.png"
          height="301"
          width="253"
          fluid
          alt="backstage"
        ></b-img></a>
        <br><br><a class="boton" href="#">Tras Bambalinas</a><br><br>
        <!-- <a href="#" id="tre">Tras bambalinas</a> -->
      </div>
      <div class="am">
        <a href="frontend\src\views\foro.vue" title="Foro"><b-img
          src="http://cdn.onlinewebfonts.com/svg/img_96727.png"
          height="301"
          width="253"
          fluid
          alt="forum"
        ></b-img></a>
        <br><br><a class="boton" href="#">Foro</a><br><br>
        <!-- <a href="#" id="tre">Tras bambalinas</a> -->
        <!-- src="frontend\src\assets\foro.jpg" -->
      </div>
    </div>

    <div class="sub2">
        <iframe height="20"></iframe>
        <h2>Senarautas Destacados</h2>
        <iframe height="30"></iframe>
    </div>


    <div class="contenedor-sena">
     
        <a href="frontend\src\views\senarauta1.vue" title="Senarauta1"><b-img
        src="https://toppng.com/uploads/preview/user-font-awesome-nuevo-usuario-icono-11563566658mjtfvilgcs.png"
        height="200"
        width="200"
        fluid
        alt="Senarauta1"
      ></b-img></a>
      
        <a href="frontend\src\views\senarauta2.vue" title="Senarauta2"><b-img
        src="https://toppng.com/uploads/preview/user-font-awesome-nuevo-usuario-icono-11563566658mjtfvilgcs.png"
        height="200"
        width="200"
        fluid
        alt="Senarauta2"
      ></b-img></a>
     
        <a href="frontend\src\views\senarauta3.vue" title="Senarauta3"><b-img
        src="https://toppng.com/uploads/preview/user-font-awesome-nuevo-usuario-icono-11563566658mjtfvilgcs.png"
        height="200"
        width="200"
        fluid
        alt="Senarauta3"
      ></b-img></a>
   
        <a href="frontend\src\views\senarauta4.vue" title="Senarauta4"><b-img
        src="https://toppng.com/uploads/preview/user-font-awesome-nuevo-usuario-icono-11563566658mjtfvilgcs.png"
        height="200"
        width="200"
        fluid
        alt="Senarauta4"
      ></b-img></a>

        <a href="frontend\src\views\senarauta5.vue" title="Senarauta5"><b-img
        src="https://toppng.com/uploads/preview/user-font-awesome-nuevo-usuario-icono-11563566658mjtfvilgcs.png"
        height="200"
        width="200"
        fluid
        alt="Senarauta5"
      ></b-img></a>
    </div>

    <div><iframe height="100"></iframe></div>

  </main>
</template>

<script scr="components/footer.js">
</script>

<style scoped lang="scss">
main {
  padding-top: 8rem;
  width: 100%;
  margin-top: 120px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  background-image: url(/src/assets/fondocontacto1);
  flex-grow: 1;
  padding-top: 1rem;
}

 h2{
    font-weight: 800;
    justify-content: center;
    text-align: center;
    font-family: sans-serif;
}

.boton {
border: 1px solid #f8570c; /*anchura, estilo y color borde*/
padding: 20px; /*espacio alrededor texto*/
background-color: #f8570c; /*color botón*/
color: #ffffff; /*color texto*/
text-decoration: none; /*decoración texto*/
text-transform: uppercase; /*capitalización texto*/
font-family: 'Helvetica', sans-serif; /*tipografía texto*/
border-radius: 50px; /*bordes redondos*/
text-align: center;
direction: flex;
flex-direction: row;
align-items: center;
}

.contenedor {
  /*position: relative;*/
  height: 500px;
  width: 100%;
}

iframe {
//   width: 100%;
//   height: 500px;
  .sub {
    align-items: center;
  }
}
.contenedor-serie {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  width: 100%;
}

.contenedor-sena {
  flex-direction: row;
  display: flex;
  justify-content: space-evenly;
  width: 100%;
  align-items: center;
}

.am {
  direction: flex;
  flex-direction: row;
  align-items: center;
}


</style>
