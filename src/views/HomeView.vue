<template>
  <main>
    <br />
    <h1>Welcome to a better version of reddit more powerful than reddit.<br /> Welcome to Upvote.</h1>
    <br /> <br />
 <div class="flex justify-center space-x-4">
    <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-1 px-1.5 rounded">
      <router-link to="/about">About Upvote</router-link>
    </button>
    <a href="https://github.com/upvoteapp/upvote" class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-1 px-1.5 rounded">
      Project Github
    </a>
  </div>
  <br />

  <h5 class="text-right"><span class="server_time"></span>
   ©2023 aviance.</h5>
</main>
</template>
<style scoped>
main {
  background-color: white;
  font-family: 'Poppins', sans-serif;
  position: absolute;
  top: 50%;
  font-size: x-large;
  left: 50%;
  margin-right: -50%;
  width: 50%;
  text-align: center;
  transform: translate(-50%, -50%);

}
.text-right {
  text-align: right;
  font-size: xx-small;
  color: gray;
  margin-right: 1em;
}
</style>
