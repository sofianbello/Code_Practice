<template>
  <div id="content-wrapper">
    <Header/>
    <div class="grid">
      <div class="grid-itemA"> 
            <img src="https://images.unsplash.com/photo-1626193864236-8938b5854459?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1075&q=80"/> 
            <p class="grid-text">Work 1</p>
      </div>
      <div class="grid-itemB">
            <img src="https://images.unsplash.com/photo-1625737186162-5766a7289b5a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1480&q=80"/> 
            <p class="grid-textBig">Work 2</p>
      </div>
      <div class="grid-itemA">
          <img src="https://images.unsplash.com/photo-1631603296585-8e7e9a7a8f7e?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2160&q=80"/> 
            <p class="grid-text">Work 3</p>
      </div>
    </div>
    <Footer/>
  </div>  
</template>

<script>

export default {
}
</script>

<style scoped>
html, body {
display: flex;
flex-direction: row;
background-color: deepskyblue;
}



.fill {
    display: flex;
    justify-content: center;
    align-items: center;

}

.fill-img {
    flex-shrink: 0;
    min-width: 100%;

}


div.grid {
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: 1fr 1fr;
    grid-gap: 1rem;
    padding-top: 1rem;
    padding-bottom: 1rem;
    position: relative;





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

.grid-itemB {
    display: flex;
    color: rgb(255, 251, 247);
    font-size: 24pt;
    justify-content: center;
    height: 90vh;
    align-items: center;
}

.grid-text {
    position:absolute;
    align-self: end;
}

.grid-textBig {
    position:absolute;
    align-self: center;
    
    font-size: 280pt;
    color: rgb(222, 253, 45);
}

img {
    object-fit: cover;
    width: 100%;
    height: 100%;
    object-fit: stretch;

}
</style>