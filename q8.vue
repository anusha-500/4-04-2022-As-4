<template>
<div>
    <h1>Question -8</h1>
    <p> using p-tag</p>
<p @click="result()">p-tag</p>
<textarea id="sample"> </textarea>
</div>
</template>
<script>
export default {
name: "QuesT8",
data() {
return {
text: "",
};
},
methods: {
result() {
this.text = document.write("" + document.getElementById("sample").value);
},
},
};
</script>