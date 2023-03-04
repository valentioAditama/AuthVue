<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<style>
@import './Login.css';
</style>

<template>
    <div class="container">
        <div class="row contentCenter">
        <div class="col-md-6">
            <img src="../../../assets/login.gif" class="img-fluid" alt="image">
        </div>
        <div class="col-md-6">
            <form>
                <div class="mb-3">
                    <h3>Welcome</h3>
                    <h6 class="subTitle">Login first before entering</h6>
                </div>
                <div class="mb-3">
                    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Email">
                </div>
                <div class="mb-3">
                    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
                </div>
                <div class="mb-3">
                    <RouterLink to="/register">Don't Have Account?</RouterLink>
                </div>
                <button type="submit" class="btn btn-primary container">Login</button>
            </form>
        </div>
    </div>
    </div>
</template>