<template>
    <nav class="navbar-main">
        <div class="ul-button"> HOME </div>
        <div class="ul-button"> CATALOGO </div>
        <div class="name-shop">{{ nameShop }}</div>
    </nav>
</template>

<script>
export default {
  data () {
    return {
      nameShop: 'PHOENIX'
    }
  },
  name: 'Navbar'
}
</script>

<style lang="scss" scoped>
@import "@/styles/colors.scss";
@import "@/styles/typography.scss";

.navbar-main{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 50px;
  background-color: $light-gray;
  font-weight: lighter;
}
.navbar-main div{
  min-width: 3em;
  margin: 1em;
}

</style>
