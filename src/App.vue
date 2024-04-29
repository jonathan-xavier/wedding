
<template>
  <div>
    <div class="container-navbar">
      <span class="logo">J & J</span>
      <div class="nav-bar">
        <ul>
          <li><a href="">HOME</a></li>
          <li><a href="">CERIMÔNIA</a></li>
          <li><a href="">LISTA DE PRESENTES</a></li>
          <li><a href="">CONFIRME SUA PRESENÇA</a></li>
        </ul>
      </div>
     
    </div>
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



<style lang="scss" scoped>

.nav-bar{
 // background-color: red;
 //width: 50%; 
 display: flex;
 align-items: center;
 justify-content: center;
  ul{
   // background-color: #dddddd;
  }
  li{
    display: inline;
    float: left;
    margin-right: 20px;
    
  }
  a{
    display: block;
    padding: 8px;
    //background-color: #dddddd;
    text-decoration: none;
    color: black;
  }
  a:hover{
    color: white;
    background-color: black;
    text-transform: uppercase;
  }

  list-style-type: none;
  margin: 0;
  padding: 0;
}

.logo{
  color: black;
  font-size: 20px;
  font-weight: bold;
}

.container-navbar{
  display: flex;
  justify-content: space-around;
  align-items: center;
}
</style>
