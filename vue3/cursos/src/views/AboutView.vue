<template>
  <div class="about">
    <h1>Esta pagina es donde se hace las pruebas de {{ appName }}</h1>
    <button class="btn waves-effect waves-light" type="submit" name="action">Guardar
    <i class="material-icons right">save</i>
  </button>
     </div>
</template>

<script>

export default {
  name: 'About',
  data(){
    const appName=process.env.VUE_APP_NAME
    return{
      appName
    }
  }
}
</script>