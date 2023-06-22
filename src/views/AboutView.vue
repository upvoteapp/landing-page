<template>
  <main>
    <br />
    <h1>About Upvote</h1>
    <br /> <br />
    <div class="cemter">
    <p class="wrap" style="font-size: small;">Upvote is an attempt of making the fastest & most powerful machine control panel, allowing you to be able to have the same functionality as Pterodactyl being based on a custom engine, all written in the famous language, javascript. If you are interested in contributing to the project, click on the Github button below to be redirected to the project, otherwise, see you on the flip side!  </p>
    <br />
    <div class="flex justify-center space-x-4">
      <a href="https://github.com/upvoteapp/upvote" class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-0.5 px-1.5 rounded">Github</a>
      <a class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-0.5 px-1.5 rounded">
        <RouterLink to="/">Home</RouterLink>
      </a>
    </div>
    <br />
    </div>
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
.center {
  margin: auto;
  width: 50%;
  padding: 10px;
}
.wrap {
  white-space: pre-wrap;       /* css-3 */
  white-space: -moz-pre-wrap;  /* Mozilla, since 1999 */
  white-space: -pre-wrap;      /* Opera 4-6 */
  white-space: -o-pre-wrap;    /* Opera 7 */
  word-wrap: break-word;       /* Internet Explorer 5.5+ */

}
.text-right {
  text-align: right;
  font-size: xx-small;
  color: gray;
  margin-right: 1em;
}
</style>