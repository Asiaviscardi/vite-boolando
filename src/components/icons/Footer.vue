<script>
export default {
    name:'Footer'

}
</script>

<template>

<div class="inferiore flex">

<div class="ineriore-info flex">

    <div id="info">

        <h4>Booleando s.r.l</h4>

        <div class="info-box flex">
            
            <span>Prova</span>

            <span>Prova</span>

            <span>Prova</span>
            
        </div>

    </div>

    <div id="social">

        <h4>Trovaci anche su</h4>

        <div class="info-box flex">

            <i class="fa-brands fa-square-twitter"></i>
            <i class="fa-brands fa-square-twitter"></i>
            <i class="fa-brands fa-square-twitter"></i>
            <i class="fa-brands fa-square-twitter"></i>
            <i class="fa-brands fa-square-twitter"></i>

        </div>

    </div>

</div>

</div>
  
</template>

<style scoped lang="scss">

.flex{
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.inferiore{
    padding: 20px;
    background-color: black;
    height: 90px;
}

.ineriore-info{
    height: 100%;
    width: 100%;
    justify-content: space-between;

    #info{
    width: 200px;
    height: 100%;
    color: white;
    }

    #social{
    width: 200px;
    height: 100%;
    color: white;
    }
}


</style>