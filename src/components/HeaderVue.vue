<template>
    <div class="content">
        <div>
            <img src="../assets/fusino.jpg" alt="example">
        </div>
        <div class="title">
            <h1 class="name">Constanza Desiree Carnet</h1>
            <h2>Full stack web developer</h2>
        </div>
    </div>
</template>

<script setup>
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
</script>

<style scoped lang="scss">
.name {
    color: white;
    font-size: 40px
}

.content{
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-gap: 2px;
    background: rgb(2,0,36);
    background: linear-gradient(180deg, rgba(2,0,36,1) 0%, rgba(20,3,43,1) 0%, rgba(9,12,123,1) 35%, rgba(6,140,200,1) 75%, rgba(23,174,205,1) 87%);
    background-size: cover;
}
.title{
    position:relative;
    top: 30%;
    left: -15%;
}

img{
    border-radius:50%;
    width:40%;
    height: auto;
    margin-top: 10%;
    margin-bottom: 10% ;
}

@media screen and (max-width: 700px) {
      .content{
        grid-template-columns: 1fr;
      }
      .title{
        top: 0;
        left: 0px;
      }
    }

    @media screen and (min-width: 1170px) {
      .title{
        font-size:x-large;
      }
    }
</style>