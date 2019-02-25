<template>
  <div>
    <form @submit.prevent="login()">
      <div class="card z-depth-0" style="width: 440px; padding: 50px 10px; margin: 80px auto">
        <div class="row">
          <p class style="font-size: 20px; padding: 0 10px; font-weight: 400">Login
            <br>
            <small>Sign in with your College Situation info</small>
          </p>
          <div class="input-field col s12">
            <input id="email" type="email" v-model="email" required class="validate">
            <label for="email">Email</label>
          </div>
        </div>

        <div class="row">
          <div class="input-field col s12">
            <input id="password" required type="password" v-model="password" class="validate">
            <label for="password">Password</label>
            <br>
            <br>
            <br>
            <button
              class="btn waves-effect waves-light z-depth-0"
              style="width: 100%"
              type="submit"
              name="action"
            >Login</button>

            <br>
            <br>

            <p align="right">
              Don't have an account yet?
              <a href="#">Signup Now</a>
            </p>
          </div>
        </div>
      </div>
    </form>
  </div>
</template>

<script>
import axios from "axios";
export default {
  data() {
    return {
      email: null,
      password: null
    };
  },

  methods: {
    login() {
      console.log(this.email, this.password);
      M.toast({ html: "Authenticating", classes: "red", displayLength: 1000 });
      axios({
        url: "https://thecollegesituation.herokuapp.com/api/v1/student/login",
        method: "post",
        data: {
          email: this.email,
          password: this.password
        }
      })
        .then(user => {
          let login = this;
          if (user) {
            console.log(user);
            M.toast({
              html: "Login successful 😇",
              classes: "green",
              displayLength: 2000,
              completeCallback: function() {
                login.$router.replace({ name: "addschool" });
                M.toast({ html: "Loading dashboard", classes: "green" });
              }
            });
          } else{
             M.toast({ html: "Invalid Login details", classes: "red" });
          }
        })
        .catch(err => {
          console.log("could not log you in", err.message);
          
        });
    }
  }
};
</script>

<style>
</style>
