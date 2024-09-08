<template>

    <section id="product" class="market">
        <div class="text">
            <h1><strong>Welcome</strong></h1>
            <h2>To our product</h2>
        </div>
        <div class="horizontal-scroll">
            <div class="container">
                <div class="card">
                    <img src="../assets/1.png" alt="">
                    <p>Lorem ipsum dolor sit amet.</p>
                </div>
                <div class="card">
                    <img src="../assets/2.png" alt="">
                    <p>Lorem ipsum dolor sit amet.</p>
                </div>
                <div class="card">
                    <img src="../assets/3.png" alt="">
                    <p>Lorem ipsum dolor sit amet.</p>
                </div>
                <div class="card">
                    <img src="../assets/1.png" alt="">
                    <p>Lorem ipsum dolor sit amet.</p>
                </div>
                <div class="card">
                    <img src="../assets/2.png" alt="">
                    <p>Lorem ipsum dolor sit amet.</p>
                </div>
                <div class="card">
                    <img src="../assets/3.png" alt="">
                    <p>Lorem ipsum dolor sit amet.</p>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {

}
</script>
<style scoped>
.market{
    display: flex;
    flex-wrap: wrap;
    padding: 100px;
    gap: 3rem;
}
.text h1{
    font-size: 3rem;
}
.text{
    width: 100%;
}
.container{
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-around;
    gap: 3rem;
    width: 100%;
}
.card img{
    width: 300px;
}
.card{
    width: 28%;
    box-shadow: 0 0 10px black;
    border-radius: 9px;
    padding: 10px;
    height: 40%;
}
</style>