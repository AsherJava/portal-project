<template>
    <div>
        <Button @click="value1 = true" type="primary">Open</Button>
        <Drawer title="Basic Drawer" :closable="false" v-model="value1">
            <p>Some contents...</p>
            <p>Some contents...</p>
            <p>Some contents...</p>
        </Drawer>
    </div>
</template>

<script>
    export default {
        name: "test",

    }
</script>

<style scoped>

</style>
