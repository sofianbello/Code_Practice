<template>
  <div id="content-wrapper">
    <Header/>
    <div class="grid">
      <div class="grid-itemA"><div>Photo</div></div>
      <div class="grid-itemA"><div>Description</div></div>
    </div>
    <Footer/>
  </div>    
</template>

<script>

export default {
}
</script>

<style scoped>
body {
display: flex;
flex-direction: row;


}



div.grid {
    display: grid;
    grid-template-columns: 1fr 2fr;
    grid-template-rows: 1fr;
    grid-gap: 1rem;
    padding-top: 1rem;
    padding-bottom: 1rem;




}
.grid-itemA {
    display: flex;
    color: rgb(255, 251, 247);
    font-size: 24pt;
    background-color: gray;
    justify-content: center;
    height: 90vh;
    align-items: center;

    


}
</style>
