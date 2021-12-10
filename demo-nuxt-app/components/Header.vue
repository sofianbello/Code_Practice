<template>
    <div id="navigation-wraper">
        <NuxtLink to="/" class="nav-element">Home</NuxtLink>
        <NuxtLink to="/work" class="nav-element">Work</NuxtLink>
        <NuxtLink to="/about" class="nav-element">About</NuxtLink>
    </div>
</template>

<style scope>
#navigation-wraper{
    display: flex;
    justify-content: center;
    background-color: black;
}
.nav-element {
    display: flex;
    flex-direction: row;
    color: rgb(255, 251, 247);
    padding: 1rem;
    text-decoration: none;
}

</style>