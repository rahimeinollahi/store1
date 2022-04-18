<template>
    <div class="container p-3">
        <div class="row">
            <div class="col-sm-4"></div>

            <div class="col-sm-4 bg-light">  
                <h4>welcome to Shop </h4>
                <div>
                    <img class="rounded-circle img-login" src="../../src/assets/logo.png"/>
                </div>
                
                <form action="" id="form-id" method="post" name="login-form">
                    <label for="username">userName :</label>
                    <input type="text" name="userNaem" id="userName" class="form-control" v-model="userName">
                    <br>
                    <label for="password">Password "</label>
                    <input type="text" name="password" id="password" class="form-control" v-model="password" >

                    <input type="button" value="Login" id="submit" @click="checkLogin()" class="btn btn-block btn-info w-100 mt-1 mb-1"/>
                </form>

                    <span id="forgot-password" class="">forgot password | click here</span>
            </div>

            <div class="col-sm-4"></div>
        </div>
    </div>
</template>

<script>
    export default {
        name:'LoginPage',
        data(){
            return{
                userName:'rahim',
                password:'1369'
            }
        },
        methods:{
            checkLogin(){
                if(this.userName =="rahim" && this.password=="1369"){
                    this.$router.push('/')
                    }
                else{
                    alert('invalid username or password')
                    this.userName='',
                    this.password=''
                }
            }
        }
    }
</script>

<style lang="scss" scoped>
.img-login{
    width: 120px;
    height: 120px;
}
</style>
