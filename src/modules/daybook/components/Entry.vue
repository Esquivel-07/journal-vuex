<template>
    <div class="entry-container mb-3 pointer p-2" @click="$router.push( { name: 'entry', params: { id: 10 } } )">
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">28</span>
            <span class="mx-1 fs-5">Mar</span>
            <span class="mx-2 fs-6 fw-light">2024, Jueves</span>
        </div>

        <div class="entry-description">
            skdsmds dsnvksd vksdnjkv sdv iosdv sdjk vjhsd vks djkv hsd vjs dv jhsdbvisd v sdkhlv hlsd vjs dv ksdb visd kv sdjkv hsd vjklsd jkv sdjklv sd vas dkv sdjkiv jsd vjksd jkv sdj vjsd vjsd jiv sdjhv jhsd vjn sdv sdl viusduv e sao cjas licas kc ashcñasc asiuc asv apsv as cas vc asiuv av
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

    .entry-container {

        border-bottom: 1px solid #2c3e50;
        transition: 0.2s all ease-in;

        &:hover {

            background-color: lighten($color: grey, $amount: 45);
            transition: 0.2s all ease-in;
        }

        .entry-description {

            font-size: 14px;
        }
    }
</style>