<template>
    <button class="btn btn-primary">
        <i :class="iClass"></i>
    </button>
</template>

<script>
export default {

    props: {

        icon: {

            type: String,
            default: 'fa-plus'
        }
    },
    computed: {

        iClass() {

            return `fa fa-1x ${ this.icon }`
        }
    }
}
</script>

<style lang="scss" scoped>

    button {
        position: fixed;
        bottom: 20px;
        right: 20px;
        width: 40px;
        height: 40px;
        border-radius: 100%;
    }
</style>