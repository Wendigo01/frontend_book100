<template>
    <div class="container">
        <h1 class="display-5 text-center">Könyvek</h1>
        <div class="row">
            <div class="col-12 col-md-3" v-for="book in books">
                <div class="card">
                    <img :src="imgUrl + book.ImageName" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">{{ book.Title }}</h5>
                        <p class="card-text">{{ book.Author }}</p>
                        <p class="card-text">{{ book.Title }}</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>