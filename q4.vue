<template>
    <div>
        <head>Assignment-4</head>
        <h1>Question 4</h1>
        <p> fetch the data from the given url</p>
      
        </div>
</template>
<script>
//var axios = require("axios").default;
export default {
  name: "q4ANS",
  data() {
    return {
        async created() {
  // GET request using fetch with async/await
  const response = await fetch("https://jsonplaceholder.typicode.com/posts/1/comments");
  const data = await response.json();
  this.totalVuePackages = data.total;
}
    }
    }
  }

  </script>
    