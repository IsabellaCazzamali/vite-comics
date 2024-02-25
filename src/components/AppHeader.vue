<script>
export default {
    name: 'AppHeader',
}
</script>

<template>

    <header>
        <div class="logo">
        <img src="/img/dc-logo.png" alt="logo DC comics">
        </div>
    
        <nav>
            <ul class="main_menu">
                <li><a href="#">Characters</a></li>
                <li><a href="#" class="active">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Collectibles</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">Fans</a></li>
                <li><a href="#">News</a></li>
                <li><a href="#">Shop</a></li>
            </ul>
        </nav>
    </header>

</template>


<style scoped>

header {
  text-align: center;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 70%;
  max-width: 1176px;
  margin: auto;
  background-color: white;
  padding-top: 1.5rem;

  & .main_menu {
    list-style: none;
    display: flex;
    gap: 1.5rem;
    align-items: center;
    padding-top: 0.5rem;

    & a {
      text-decoration: none;
      color: var(--dc-dark_grey);
    }

    & a.active {
        color: var(--dc-lighter_primary);
    }
  }
}

</style>