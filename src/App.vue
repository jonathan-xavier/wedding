<template>

  <!-- navbar -->
  <div>
    <nav class="navbar navbar-expand-lg bg-dark fixed-top my-container" data-bs-theme="dark">
      <div class="container-fluid main-nav">
        <span class="navbar-brand">J & J</span>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup"
          aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse buttons-nav justify-content-center" id="navbarNavAltMarkup">
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

  <!-- fim navbar -->


  <!-- inicio head -->
  <div class="my-main">
    <img src="./assets/we.jpg" alt="">
    <div >

    </div>
    <vr class="line" style="color: black; width: 78px; height: 10px; background-color: black;"/>
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
.buttons-nav {

  a {
    color: #fff;
    /* color: black; */

  }

  a:hover {
    color: black;
  }
}

.my-container {
  background-color: #91A8D2 !important;
  padding-right: 20px;
  letter-spacing: 4px;
  box-shadow: 0px 1px 0px;
}

.main-nav {
  display: flex;
  align-items: center;
  justify-content: center;
}

.navbar-brand {
  color: black;
  font-weight: bold;

}

.my-main {
  /* background-color: red !important; */
  margin-top: 57px;
  height: 800px;
  display: flex;
  border-bottom: 1px solid black;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  /* background-color: #60708C ; */
  img{
    margin-top: 30px;
    border-radius: 10px 10px 10px 10px;
    height: 700px;
  }

}

.line{
  position: relative;
  background-color: black;
}
</style>
