<template>
 <header>
  <router-link to="/">
    <h1><span>Vue</span>Movie</h1>
  </router-link>
 </header>
 <main>
  <router-view/>
 </main>

</template>
<script>

export default {

}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;

  &::selection {
    background: transparentize($color: #42b883, $amount: 0.5);
  }
}
body {
  background-color: #35495e;
}
a {
  text-decoration: none;
}
header {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 10px 15px;
  background-color: #2C3d4e;
  box-shadow: 0px 0px 6px rgba(0,0,0,0.1);

  h1 {
    color: #fff;
    font-size: 28px;

    span {
      color:#42b883;
    }
  }
}
</style>
