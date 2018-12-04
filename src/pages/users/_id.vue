<template>
    <div>
        {{id}}
    </div>
</template>

<script>
export default {
    name:'',
    data() {
        return {
            id: this.$route.params.id,
        };
    },
    mounted() {
    }
};
</script>

<style scoped>

</style>