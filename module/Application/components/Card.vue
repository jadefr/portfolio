<template>
    <div class="card-component-container">
        <section>
            <h1>CARD</h1>
        </section>
    </div>
</template>

<script type="module">
    export default {
        props: {
            title: String
        }
    }
</script>

<style  lang="scss" scoped>
    .card-component-container {
        background: red;
        color: greenyellow;
        font-size: 2em;

        section {
            padding: 200px;
            background: yellow;
        }
    }
</style>