<script>
export default {
    name:'Header'

}
</script>

<template>

<div class="barra flex">

<div id="categorie pad">

    <ul class="flex">

        <li><a href="">Donna</a></li>

        <li><a href="">Uomo</a></li>

        <li><a href="">Bambini</a></li>

    </ul>

</div>

<div class="lb pad flex">

    <img id="logo" src="../../../src/assets/booleanlogo.png" alt="">

</div>

<div class="funzioni pad">

    <!-- <i class="fa-regular fa-user" style="color: #ffffff;"></i>

    <i class="fa-regular fa-heart" style="color: #ffffff;"></i>

    <i class="fa-solid fa-bag-shopping" style="color: #ffffff;"></i> -->

    
</div>

</div>
  
</template>

<style scoped lang="scss">

a{
    text-decoration: none;
    color: white;
    
}

li{
    list-style: none;
    margin-right: 7px;
}

.barra{
    width: 100%;
    height: 50px;
    background-color: #ff6900;
    border-bottom: 2px solid rgba(169, 169, 169, 0.5);
}

.flex{
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.lb{
    align-items: center;
}

#logo{
    width: 100px;
}

.funzioni i{
    cursor: pointer;
    margin-right: 3px;
    
}



</style>