
<template>
  <div>
    <h1>Jamy memes</h1>
  </div>
  <div id="carouselExample" class="carousel slide">

  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="./assets/jamy2.png" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="./assets/jamy.png" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="./assets/jamty3.png" class="d-block w-100" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>

</template>

<script >

export default{
  data:function(){
    return {
      code: '',
    }
  },

  computed:{

  },

  methods:{
    teste(){
      alert('funciona')
    }

  },

  mounted(){

  }
}
</script>



<style scoped>

</style>
