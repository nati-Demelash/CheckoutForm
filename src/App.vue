<template>
 <TheHeader/>
 <checkout-form/>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import CheckoutForm from './components/CheckoutForm.vue'
export default {
  name: "App",
  components: {
    TheHeader,
    CheckoutForm
  },
};
</script>

<style>
*{
  margin:0;
  padding:0;
}
header {
  width: 100%;
  margin:10px;
  text-align: center;
}
header .logo {
  padding: 10px;
  /* margin: 10px 13rem; */
}

header .logo img{
   width: 60px;
}
</style>
