<template>
    <div class="container mt-2">
        <div class="">
            <div class="row bg-light">
                <!-- <div class="col-sm-4 p-2 border-end">Create Free Account </div>
                <div class="col-sm-4 p-2">Login In Pannel</div>
                <div class="col-sm-4 p-2"></div> -->
                <router-link class="col-sm-4 nav-link border-end" to="/creat-account"> Create Account</router-link>
                <router-link class="col-sm-4 nav-link" to="/pannel"> Login In pannel</router-link>
                <router-link class="col-sm-4 nav-link" to="/"> </router-link>
            </div>
            <div class="row">
                <div class="col-sm-8">
                    <img src="../../src/Images/homePhoto.webp" alt="homePhoto">
                </div>
                <div class="col-sm-4">
                    <h1 class="display-3 text-info">Create Store channel only with one simple click</h1>
                    <p>Create website bye yourselft and simply and in one minutes.. join to 100,000 user, Then make your site.</p>
                    <p>LifeCycle support - 24 hour - Free consultant...</p>
                </div>
            </div>
        </div>
        <div>
            <h3 class="display-3 text-success">Every thing you need to build successfull website</h3>
        </div>

        <div class="row ">

            <div class="col-sm-3 ">
                <img id="img-mobile" class=" d-flex justify-content-center" src="../../src/Images/mobile_image.webp" alt="mobile-image"><br>
                 <p>Ready to mobile users</p>
            </div>

            <div class="col-sm-3 ">
                <img id="img-mobile" class=" d-flex justify-content-center" src="../../src/Images/support-image.webp" alt="mobile-image"><br>
                 <p>5 Start Support</p>
            </div>

            <div class="col-sm-3 ">
                <img id="img-mobile" class=" d-flex justify-content-center" src="../../src/Images/rannk-image.webp" alt="mobile-image"><br>
                 <p>Top Rank in google</p>
            </div>

            <div class="col-sm-3 ">
                <img id="img-mobile" class=" d-flex justify-content-center" src="../../src/Images/fac-image.webp" alt="mobile-image"><br>
                 <p>Build website with your taste</p>
            </div>   
            
            <div>
                <h2>appropriate format to build store...</h2>
                <p>Templates tailored to your needs</p>
            </div>

            <div>
                <h3 class="text-success">Now create your store website</h3>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name:'MainPage'
    }
</script>

<style lang="scss" scoped>
#img-mobile{
    width: 100px;
    height: 100px;
}
</style>