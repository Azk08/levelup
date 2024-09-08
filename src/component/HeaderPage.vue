<template>
    <section id="home" class="home">
        <div class="text">
            <h1><strong>Welcome</strong></h1>
            <h2>To our market</h2>
        </div>
        <div class="porduct-container">
            <div class="product">
                <img src="../assets/1.png" alt="">
                <img src="../assets/3.png" alt="">
                <img src="../assets/2.png" alt="">
            </div>
        </div>
    </section>
</template>
<script>
export default {

}
</script>
<style scoped>
.home {
    display: flex;
    flex-wrap: wrap;
    padding: 100px;
}

.text h1 {
    font-size: 3rem;
}

.text {
    width: 100%;
}

.product img {
    width: 300px;
}

.product {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    align-items: center;
    text-align: center;
}
</style>