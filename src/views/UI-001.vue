<template>
  <div class="flex-center">
    <div
      class="login-card"
      style="width: 360px; background: #191919; box-shadow: 0 0 30px rgba(0, 0, 0, 0.1); padding: 3rem;border-radius: 24px; color:white;"
    >
      <form class="login-form">
        <h1>Create a new account</h1>
        <div class="form-group">
          <input
            type="text"
            placeholder="Your Name"
            style="border: 2px solid purple;border-radius: 24px;padding: 14px;text-align: center;outline: none; width: 180px;"
            id="name"
          />
        </div>
        <div class="form-group">
          <input
            type="password"
            id="password"
            placeholder="Password"
            style="border: 2px solid purple;border-radius: 24px;padding: 14px;text-align: center;outline: none; width: 180px;"
          />
          <button
            type="submit"
            id="submit"
            style="border: 2px solid purple;border-radius: 24px;padding: 7px;text-align: center;  margin-top: 1rem;"
          >
            Sign up
          </button>
        </div>
      </form>
    </div>
  </div>
</template>

<style lang="css" scoped>
h1 {
  margin-top: 0;
}

.form-group {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 1rem;
}
#submit:hover {
  color: #255784;
  background: #00ff00;
  box-shadow: 0 0 10pc #2196f3, 0 0 40pc #2196f3, 0 0 80pc #2196f3;
}

#name:hover,
#password:hover {
  background: #02a0a5;
}
</style>
