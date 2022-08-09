<template>
    <div>
<img src="https://i5.walmartimages.ca/images/Enlarge/238/171/6000203238171.jpg" alt="">
<img src="https://images.heb.com/is/image/HEBGrocery/001247932?fit=constrain,1&wid=800&hei=800&fmt=jpg&qlt=85,0&resMode=sharp2&op_usm=1.75,0.3,2,0" alt="">
    </div>
</template>

<script>
    export default {
        name: "product-gallery"
    }
</script>

<style scoped>
div {
      display: grid;
  grid-auto-flow: column;
  place-items: center;
}

img {
max-width: 25vw ;
height: 35vh;
}
</style>