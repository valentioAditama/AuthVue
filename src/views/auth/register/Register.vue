<style>
@import "./Register.css";
</style>

<template>
  <div class="container">
    <div class="row contentCenter">
      <div class="col-md-6">
        <img src="../../../assets/register.gif" class="img-fluid" alt="image" />
      </div>
      <div class="col-md-6">
        <form @submit.prevent="register">
          <div class="mb-3">
            <h3>Register</h3>
            <h6 class="subTitle">Create your first account</h6>
          </div>
          <div class="mb-3">
            <input
              type="email"
              class="form-control"
              aria-describedby="emailHelp"
              placeholder="Email"
              name="email"
              v-model="email"
              required
            />
          </div>
          <div class="mb-3">
            <input
              type="password"
              class="form-control"
              placeholder="Password"
              name="password"
              v-model="password"
              required
            />
          </div>
          <div class="mb-3">
            <input
              type="password"
              class="form-control"
              placeholder="Confirm Password"
              name="confirmPassword"
              v-model="confirmPassword"
              required
            />
          </div>
          <div class="mb-3">
            <RouterLink to="/">Have Account?</RouterLink>
          </div>
          <button type="submit" class="btn btn-primary container">
            Register
          </button>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
import axios from "axios";

export default {
  data() {
    return {
      email: "",
      password: "",
      confpassword: "",
    };
  },

  methods: {
    async register() {
      if (this.password !== this.confirmPassword) {
        alert("Passwords do not Match");
        return;
      }

      const payload = {
        email: this.email,
        password: this.password,
        confpassword: this.confirmPassword,
      };

      const response = await axios.post(
        "http://interview.pluginesia.com/register",
        payload
      );
      console.log(response.data);
    },
  },
};
</script>
