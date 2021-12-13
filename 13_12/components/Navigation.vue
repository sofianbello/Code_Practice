<template>
    <nav>
        <NuxtLink to='/Twitch'>Twitch</NuxtLink>
        <NuxtLink to='/Youtube'>YouTube</NuxtLink>
        <!-- <NuxtLink to='/'>Kontakt</NuxtLink> -->
    </nav>
</template>

<script>
export default {

};
</script>

<style>

nav {
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 20px;
    padding: 30px 0;
}

nav div {
    font-size: 1.5rem;
}

nav a {
    font-size: 1.5rem;
    text-decoration: none;
    color: #000;
}

</style>
