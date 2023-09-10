<template>
    <div class="card">
        <div class='card__header'>
            <slot name="title">title</slot>
        </div>
        <div class="card__body" :style="{ height:height}">
            <slot name="body">Default Content</slot>
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
.card {
    background-color: #1E1E1E;
    border: 1px solid white;
    border-radius: 8px;

    .card__header {
        border-bottom: 1px solid white;
        padding: 1rem;
    }

    .card__body {
        padding: 2rem;
        overflow: hidden;
    }
}
</style>