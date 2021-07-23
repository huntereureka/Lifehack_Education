<template>
  <div class="container">
    <form @submit.prevent="handleLogin">
      <div class="mb-3">
        <label for="formid" class="text-start form-label">Email address</label>
        <input
          type="email"
          class="form-control"
          id="formid"
          aria-describedby="emailHelp"
        />
      </div>
      <div class="mb-3">
        <label for="formpassword" class="form-label">Password</label>
        <input type="password" class="form-control" id="formpassword" />
      </div>
      <div class="buttonBox">
        <button
          type="submit"
          class="btn btn-primary px-4 py-2 mt-4 align-middle"
        >
          Submit
        </button>
      </div>
    </form>
  </div>
</template>

<script>
export default {
  name: "LoginForm",

  methods: {
    handleLogin() {
      //validation
      this.$router.push({name: "Profile"})
    },
  },
};
</script>

<style scoped>
label {
  color: #374785;
  display: inline-block;
  text-align: left;
}

form {
  border: 1px solid;
  padding: 40px 30px 40px 30px;
  max-width: 420px;
  margin: 30px auto;
  background: #ffffff;
  border-radius: 15px;
}

.buttonBox {
  text-align: center;
}
</style>
