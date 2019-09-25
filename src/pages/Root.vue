<template>
    <div class="">
        <p>This is page 1 Root content</p>
        <Form />
    </div>

</template>

<script>

    import Form from 'vue-form-component-v1-test'

    export default {
        name: "root",
        components:{
            Form
        },
        data() {
            return {
                device: null
            }
        },
    }
</script>

<style>
</style>
