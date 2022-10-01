<template>
    <div class="container">
        <InputForm />
        <People />
    </div>
</template>

<script setup>
import InputForm from './InputForm.vue';
import People from './People.vue';

</script>

<style>
.container{
    display: flex;
    background-color: #1d1d1d;
}
</style>