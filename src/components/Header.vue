<template>
    <header class="container80 navbar">
      <img class="logo_img" src="../assets/img/dc-logo.png" alt="">
      <nav>
        <ul>
          <li>Characters</li>
          <li class="active">Comics</li>
          <li>Movies</li>
          <li>Tv</li>
          <li>Games</li>
          <li>Collectibles</li>
          <li>Videos</li>
          <li>Fans</li>
          <li>News</li>
          <li>Shop</li>
        </ul>
      </nav>
    </header>
</template>

<style lang="scss" scoped>

.navbar{
  height: 100px;
  align-items: center;
  display: flex;
  justify-content: space-between;
  margin: 0 auto;
  padding: 1rem 0;
}

.logo_img{
  height: 60px;
  width: 60px;
}

ul{
  list-style: none;
    align-content: center;
}

li{
  display: inline;
  text-transform: uppercase;
  padding: 1rem;
  font-weight: 700;
  font-size: 11px;
}

.active{
  color: blue;

}

</style>