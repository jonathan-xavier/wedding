<template>
  <div>
    <nav class="navbar navbar-expand-md bg-dark " data-bs-theme="dark">
      <div class="container-fluid main-nav">
        <a class="navbar-brand" href="#">J & J</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup"
          aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse buttons-nav" id="navbarNavAltMarkup">
          <div class="navbar-nav">
            <a class="nav-link" aria-current="page" href="#">HOME</a>
            <a class="nav-link" href="#">CERIMÔNIA</a>
            <a class="nav-link" href="#">LISTA DE PRESENTES</a>
            <a class="nav-link" href="#">CONFIRME SUA PRESENCA</a>
          </div>
        </div>
      </div>
    </nav>
  </div>

</template>

<script>

export default {
  data: function () {
    return {
      code: '',
    }
  },

  computed: {

  },

  methods: {
    teste() {
      alert('funciona')
    }

  },

  mounted() {

  }
}
</script>



<style lang="scss" scoped>

.buttons-nav{
 
  a{
    color:rgb(219, 219, 219);

  }
  a:hover{
    color: white;
  }
}

.main-nav{

    display: flex;
    align-items: center;
    justify-content: center;
  
}
</style>
