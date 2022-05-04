<template>
    <div class="cover">
        <img :src="coverImage" alt="">
        <p>{{coverTitle}}</p>
    </div>
</template>

<script>
export default {
    props:{
        coverImage: String,
        coverTitle: String,
    }
}
</script>

<style lang="scss" scoped>

.cover{
    width: calc(100% / 12 ) * 2;
    padding: 1rem;

        img{
            width: 100%;
                height: 200px;
                object-fit: cover;
                object-position: top;
        }
}
</style>