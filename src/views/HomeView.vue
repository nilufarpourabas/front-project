<template>
  <!-- <main id="app"> -->
    <div class="container">
      <div class="row">
        <div class="col-lg d-flex justify-content-center ">
          <Modal
          v-for="product in products"
          :key="product.bgtext"
          :product="product"
          />
        </div>
      </div>
    </div>
  <!-- </main> -->
</template>
<script>
import Modal from "../components/Modal.vue";

export default {
  name: "App",
  components: { Modal },
  data() {
    return {
      products: [
        {
          title: "Vuejs",
          discription: "green lorem njdsfjf shfhkfhjkhfjkhf",
          bgtext: "pori",
          src: require("../assets/logo.png"),
        },
        {
          title: "sara",
          discription: "vvvvvvv vvvvvvv vvvvv vvvvvvjfbsdbhsbfoweqhohwq",
          bgtext: "blue", 
          src: require("../assets/gol2.jpg"),
        },
        {
          title: "goli",
          discription: "mokhi mfkdjfndjkbjbfhjbhbdqjwrpopruwoituioe",
          bgtext: "pink",
          src: require("../assets/gol1.jpg"),
        },
        {
          title: "Iphone",
          discription: "shahi nfjnfjdsjfkjsfbkdbgfkjhgkjhg",
          bgtext: "red",
          src: require("../assets/iPhone 13.jpg"),
        },
        {
          title: "Iphone",
          discription: "shahi nfjnfjdsjfkjsfbkdbgfkjhgkjhg",
          bgtext: "red",
          src: require("../assets/iPhone 13.jpg"),
        },
        {
          title: "Iphone",
          discription: "shahi nfjnfjdsjfkjsfbkdbgfkjhgkjhg",
          bgtext: "red",
          src: require("../assets/iPhone 13.jpg"),
        }
      ],
    };
  },
};
</script>

<style>
</style>
