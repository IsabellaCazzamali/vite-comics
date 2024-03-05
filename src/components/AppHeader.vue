<script>
export default {
    name: 'AppHeader',
}
</script>

<template>

    <header>

      <nav class="container">
        <div class="logo">
          <img src="/img/dc-logo.png" alt="logo DC comics">
        </div>
        <ul class="header_menu">
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

  background-color: var(--dc-light);
  padding-top: 1rem 0;
  font-weight: 600;
  font-stretch: condensed;
  font-variant-caps: all-small-caps;
  font-size: 1.25rem;

  & nav {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    justify-content: space-between;
  }

  & .logo > img {
      width: 70px;
    }
  }

  & ul {
    list-style: none;
    display: flex;
    gap: 1rem;
    align-items: center;
    gap: 2rem;
    padding-top: 0.5rem;

    & > li {
      padding: 2rem 0;
      border-bottom: 4px solid transparent;
    }

    & > li:hover {
      border-bottom: 4px solid var(--dc-lighter_primary);
    }

    & a {
      text-decoration: none;
      color: var(--dc-dark_grey);
    }

    & a.active {
        color: var(--dc-lighter_primary);
    }
  }



</style>