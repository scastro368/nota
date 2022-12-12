<template>
   <header>
   Sofia Castro Aprendiz
    </header>

    <section>
      <article> 
        <table border="2" colspan="6" rowspan="6" >
          <tr> <th>I. información personal</th> </tr>
         <tr><td> Nombre</td><td>Sofia</td></tr>
         <tr><td>Apellido</td><td>Castro Angulo</td></tr>
         <tr><td>  Identificacion</td><td>1062235648</td></tr>
         <tr><td>  Fecha nacimiento:</td><td> 11/18/2002</td></tr>
         <tr><td>   telefono:</td><td> 3148320299</td></tr>
         <tr> <th>II. información academica</th> </tr>
         <tr><td> Nombre del programa:</td><td>   Análisis y desarrollo de sistemas de información</td></tr>
         <tr><td> Codigo ficha:</td><td>2452442</td></tr>
         <tr><td> perfil ocupacional: </td><td>desarrollador de software </td></tr>
         <tr><td>ciudad de formación:</td><td> popayán</td></tr>
         <tr> <th>III. Experiencia laboral</th> <td>Ninguna</td></tr>
         <tr></tr>
       </table>
      </article>
      <article>
        <img alt="Vue imagen" src="../assets/descarga.webp" width="300px" height="300px">
      </article>
     
    </section>

    <footer>
    <article>Correo: scastro369@misena.edu.co</article>
    <article>Telefono: 3148320299</article>
    <article>
      politica de privacidad
      <p>Creado por Sofia Castro </p>
    </article>
  </footer> 
</template>

<script>
 /*// eslint-disable-next-line
// @ is an alias to /src
import inicioCom from '@/components/inicioCom.vue'

export default {
  name: 'HomeView',
  components: {
    inicioCom 
  }
}*/
</script>
<style>
body{
  background-color: rgb(188, 243, 243);
}
header{
  height: 10vh;
  background-color: rgb(255, 255, 254);
  text-align: left;
}


section{
  height: 60vh;
  display: flex;
  justify-content: center;
  background-color: rgb(230, 203, 252);
}
article {
    border: 1px solid rgb(238, 238, 238);
    width: 50%;
 }

 footer{
   height: 10vh;
   justify-content: center;
   display: flex;
   font-size: 20px;
   background-color: antiquewhite;
   
  }

 article {
    border: 1px solid rgb(238, 238, 238);
    width: 50%;
 }


</style> 


