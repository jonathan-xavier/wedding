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
    
    <div class="title">
      <p> <i>salve a data</i></p>
      <span>
        Jonathan <br> e <br> 
        Jamilly
      </span>
      <br>
      <br>
      <span class="date">20/07/2024</span>
    </div>
    
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
  }

  a:hover {
    color: black;
  }
}

.my-container {
  background-color: #5383E8 !important;
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
  
  margin-top: 57px;
  height: 800px;
  display: flex;
  border-bottom: 1px solid black;
  flex-direction: row;
  justify-content: center;
  gap: 10px;
  align-items: center;
  img{
    border-right:  2px solid #5383E8;
    margin-top: 30px;
    border-radius: 10px 1px 0px 10px;
    height: 700px;
    padding: 0 25px 0 0;
  }

}

.title{
  padding-left: 10px;
  span {    
    color: #596163;
    font-size: 2.7rem;
    letter-spacing: 2px;
    text-transform: uppercase;
    
  }
  p{
    color: #596163;
    font-size: 1.5rem;
    letter-spacing: 3px;
    text-transform: uppercase;
    
  }

}

.date{
  font-size: 2.3rem !important;
  color: white !important;
  padding: 3px 12px;
  border-radius: 5px;
  background-color: #37579A;

}
</style>
