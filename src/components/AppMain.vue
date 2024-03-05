<script>
import ComicCard from './ComicCard.vue';
export default {
    name: 'AppMain.vue',
    components:{
      ComicCard
    },
    data(){
      return {
        comics: [
          {
          src: 'https://picsum.photos/100/100',
          text: 'Action comic 1'
        },
        {
          src: 'https://picsum.photos/100/100',
          text: 'American vampire 1976'
        },
        ]
      }
    }
}
</script>


<template>

    <main>
      <section class="comics">
        <div class="container">
          <div class="row">
            <div class="col-12" v-for="product in products">
              <ComicCard :product="product" :src="product.src" :text="product.text"></ComicCard>
            </div>
          </div>

        </div>
        <div class="main_menu">
          <a href="#"><img src="../..//img/buy-comics-digital-comics.png" alt="Icon digital comics"></a>
        </div>
        
      </section>
    </main>

</template>


<style>

main{
  margin-top: 1.5rem;
  background-color: var(--dc-dark);
  min-height: 400px;
}

.container{
  width: 70%;
  max-width: 1176px;
  margin: auto;

  & h2{
    color: var(--dc-light);
    padding-top: 5rem;
    padding-bottom: 5rem;
  }
}

.main_menu{
  background-color: var(--dc-primary);
}

</style>