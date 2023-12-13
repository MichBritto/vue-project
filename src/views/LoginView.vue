<template>
    <body class="background">
        <section class="vh-100 container justify-content-center align-items-center h-100 ">
            <div class="row d-flex justify-content-center align-items-center h-100">
                <div class="col-12 col-md-8 col-lg-6 col-xl-5">
                    
                    <div class="card bg-dark text-white card-details">
                        <div class="card-body p-5 text-center">
                            <div class="mb-md-5 mt-md-4 pb-5">
                                
                                <h2 class="fw-bold mb-2 text-uppercase">Portal de Aprovações</h2>
                                <img class="bv-logo mb-5" src="https://logodownload.org/wp-content/uploads/2020/07/boa-vista-scpc-logo-2.png" alt="">
                                
                                <div class="form-outline form-white mb-4">
                                    <input type="email" id="typeEmailX" class="form-control form-control-lg" />
                                    <label class="form-label" for="typeEmailX">Email</label>
                                </div>
                              
                                <div class="form-outline form-white mb-4">
                                    <input type="password" id="typePasswordX" class="form-control form-control-lg" />
                                    <label class="form-label" for="typePasswordX">Password</label>
                                </div>
                                <button class="btn btn-outline-light btn-lg px-5" type="submit">Login</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>          
        </section>
    </body>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
    name: "LoginView",
})
</script>

<style scoped>
.background{
 
    
    background-image: url("@/assets/bg.svg");
    background-attachment: fixed;
    background-size: cover;
}
.card-details{
    border-radius: 1rem;
}
.bv-logo{
    height: 50px;
    width: 200px;
}
</style>