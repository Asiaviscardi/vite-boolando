<script>
export default {
    name:'Main'

}
</script>

<template>

<div class="container flex">

<div class="card flex">

    <img src="../../../public/favicon.ico" alt="">

    <div class="cuore">

        <p>&hearts;</p>

    </div>

    <div class="sconto">30%</div>

    <div class="sos">Sostenibilità</div>

    <div class="specifiche">

        <div class="marca">Levi's</div>

        <h3 class="descrizione">RELAXED FIT TEE UNISEX</h3>

        <div class="prezzo">14.99 &euro; <span>29,99 &euro;</span></div>

    </div>

</div>

<div class="card flex">

<img src="../../../public/favicon.ico" alt="">

<div class="cuore">

    <p>&hearts;</p>

</div>

<div class="sconto">30%</div>

<div class="sos">Sostenibilità</div>

<div class="specifiche">

    <div class="marca">Levi's</div>

    <h3 class="descrizione">RELAXED FIT TEE UNISEX</h3>

    <div class="prezzo">14.99 &euro; <span>29,99 &euro;</span></div>

</div>

</div>

<div class="card flex">

<img src="../../../public/favicon.ico" alt="">

<div class="cuore">

    <p>&hearts;</p>

</div>

<div class="sconto">30%</div>

<div class="sos">Sostenibilità</div>

<div class="specifiche">

    <div class="marca">Levi's</div>

    <h3 class="descrizione">RELAXED FIT TEE UNISEX</h3>

    <div class="prezzo">14.99 &euro; <span>29,99 &euro;</span></div>

</div>

</div>

<div class="card flex">

<img src="../../../public/favicon.ico" alt="">

<div class="cuore">

    <p>&hearts;</p>

</div>

<div class="sconto">30%</div>

<div class="sos">Sostenibilità</div>

<div class="specifiche">

    <div class="marca">Levi's</div>

    <h3 class="descrizione">RELAXED FIT TEE UNISEX</h3>

    <div class="prezzo">14.99 &euro; <span>29,99 &euro;</span></div>

</div>

</div>

<div class="card flex">

<img src="../../../public/favicon.ico" alt="">

<div class="cuore">

    <p>&hearts;</p>

</div>

<div class="sconto">30%</div>

<div class="sos">Sostenibilità</div>

<div class="specifiche">

    <div class="marca">Levi's</div>

    <h3 class="descrizione">RELAXED FIT TEE UNISEX</h3>

    <div class="prezzo">14.99 &euro; <span>29,99 &euro;</span></div>

</div>

</div>

<div class="card flex">

<img src="../../../public/favicon.ico" alt="">

<div class="cuore">

    <p>&hearts;</p>

</div>

<div class="sconto">30%</div>

<div class="sos">Sostenibilità</div>

<div class="specifiche">

    <div class="marca">Levi's</div>

    <h3 class="descrizione">RELAXED FIT TEE UNISEX</h3>

    <div class="prezzo">14.99 &euro; <span>29,99 &euro;</span></div>

</div>

</div>

</div>
  
</template>

<style scoped lang="scss">
.container{
    flex-wrap: wrap;
    padding: 30px 140px;
    justify-content: center;
}

.flex{
    display: flex;
    justify-content: space-around;
    align-items: center;
}


.card{
    min-width: 276px;
    height: 450px;
    margin: 14px;
    flex-direction: column;
    position: relative;

    img{
    height: 70%;
    width: 100%;
    }

    .cuore{
    width: 40px;
    height: 30px;
    background-color: white;
    position: absolute;
    top: 10px;
    right: 0px;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;

    &:hover p{
        color: red;

        p{
        font-size: 23px;
        }
    }

    }

    .sconto{
    height: 15px;
    position: absolute;
    bottom: 90px;
    left: 0px;
    background-color: red;
    color: white;
    font-size: x-small;
    padding: 8px 7px;
    display: flex;
    justify-content: center;
    align-items: center;
    }

    .sos{
    height: 15px;
    position: absolute;
    bottom: 90px;
    left: 39px;
    background-color: green;
    color: white;
    font-size: x-small;
    padding: 8px 7px;
    display: flex;
    justify-content: center;
    align-items: center;
    }

    .specifiche{
    height: 15%;
    width: 100%;
    font-size: 13px;
    padding-top: 4px;

    .prezzo{
    color: red;

      span{
      color: black;
      text-decoration:line-through;
      }

    }

    }
}

</style>