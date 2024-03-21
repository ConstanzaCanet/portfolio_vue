<template>
    <div>
        <div id="content" class="col-xs-12">
            <form @submit="onSubmit" class="center-block">
                <h3>SEND ME A MESSAGE</h3>
                <div class="form-group">
                    <label for="e-address">Email address</label>
                    <input type="email" class="form-control" id="e-address" placeholder="name@example.com">
                </div>
            
                <div class="form-group">
                    <label for="name">Name</label>
                    <input type="email" class="form-control" id="name" placeholder="name@example.com">
                </div>
                
                <div class="form-group">
                    <label for="exampleFormControlTextarea1">Message</label>
                    <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
                </div>
            
                <button type="submit" class="btn btn-primary">Submit</button>
            
            </form>
        </div>
        
    </div>
</template>

<script setup>
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
</script>

<style lang="scss">
#content{
    border-top: 1px solid #9da8ac;
}

form{
    width: 100%;
    padding-top: 5%;
    background: rgb(2,0,36);
    background: linear-gradient(360deg, rgba(2,0,36,1) 0%, rgba(6,9,105,1) 14%, rgba(6,140,200,1) 64%, rgba(23,174,205,1) 88%);
}

.form-group{
    margin-left: 10%;
    margin-right: 10%;
}

.one{
    padding-top: 5%;
}
</style>