<script>
export default {
    name: 'AppMain',
}
</script>


<template>

    <main>
        <div class="container">
            <h2> -> Content goes here  </h2>
        </div>
    
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

</style>