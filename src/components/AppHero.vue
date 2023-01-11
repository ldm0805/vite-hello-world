<script>
export default {
    name: 'AppHero',
    data() {
        return {
            url: "https://www.geekandjob.com/uploads/wiki/f236a1aa005ef9a93041f294749e86d1.png"
        }
    },
}
</script>

<template>
    <div>
        <img class="m-3" :src="url" alt="vite">
        <img class="m-3" src="/img/bootstrap.jpg" alt="bootstrap">
    </div>
</template>

<style>
img {
    width: 100px;
}
</style>