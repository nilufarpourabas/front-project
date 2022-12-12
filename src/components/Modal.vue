<template>
  <div class="card w-100 me-3" style="width: 18rem">
    <img
      :src="product.src"
      style="height: 12rem"
      class="card-img-top"
      alt="..."
    />
    <div class="card-body">
      <h4 class="card-title">{{ product.title }}</h4>
      <p class="card-text overflow-hidden">{{ product.discription }}</p>
      <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
  </div>

  <!-- 
  <div class="card w-100 " style="width: 15rem; height: 23rem">
    <img
      style="width: 15rem; height: 12rem"
      :src="product.src"
      class="card-img-top"
      alt="..."
    />
    <h2>{{ product.title }}</h2>
    <div class="card-body">
      <p class="card-text">{{ product.discription }}</p>
    </div>
  </div> -->
</template>
  
  <script>
export default {
  name: "Modal",
  props: ["product"],
};
</script>

  <style>
/* body {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
} */
/* 
.card-img-top {
  width: 100%;
  height: 15vw;
  object-fit: cover;
}

.card {
  width: 100%;
  height: 15vw;
  object-fit: cover;
} */
</style>



 


  
  
  