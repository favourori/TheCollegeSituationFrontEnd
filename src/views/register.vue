<template>
  <div>
    <form @submit.prevent="login()">
      <div class="card z-depth-0 " style="width: 440px; padding: 50px 10px; margin: 120px auto">
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
            <button class="btn waves-effect waves-light" type="submit" name="action">
              Login
              <i class="material-icons right">send</i>
            </button>
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

      axios({
        url:
          "https://thecollegesituation.herokuapp.com/api/v1/student/register",
        method: "post",
        data: {
          firstName: this.firstName,
          lastName: this.lastName,
          birthday: this.birthday,
          email: this.email,
          password: this.password
        }
      }).then(registeredUser => {
        if (registeredUser) {
          console.log(registeredUser);
        }
      });
    }
  }
};
</script>

<style>
</style>
