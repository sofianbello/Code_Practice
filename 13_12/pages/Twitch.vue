<template>
    <div class="container">
        <iframe
            class="twitch-embed"
            src="https://player.twitch.tv/?channel=brivals&enableExtensions=true&muted=true&parent=localhost&player=popout&volume=0.5" 
            height="1080" 
            width="1920" 
            frameborder="0" 
            scrolling="no" 
            allowfullscreen="false"></iframe>
        <iframe
            class="twitch-chat" 
            src="https://www.twitch.tv/embed/brivals/chat?parent=localhost"
            height="1080"
            width="450">
        </iframe>
    </div>
    
</template>

<script>
export default {
    
}
</script>

<style scoped>
div.container {
    display: grid;
    grid-template-columns: 2fr 1fr;
    /* justify-content: flex-start; */
    align-items: center;

}
iframe.twitch-embed {
    max-height: auto;
    max-width: 70vw;
}
iframe.twitch-chat {
    max-height: auto;
    max-width: 20vw;
}

</style>

