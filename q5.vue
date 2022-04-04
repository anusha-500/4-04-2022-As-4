<template>
    <div>
        <head>Assignment-4</head>
        <h1>Question-5</h1>
        <p>This is errors Handling</p>
        <button @click="errorshandling()">catch</button>
    </div>
</template>
<script>
export default{
    name:"Q5DD",
    data(){
        return{

        }
    },
methods:{
errorshandling() {
try{
this.test = this.val * 45;
console.log("test",this.val);
}
catch{console.log("Error caught")}
}
}
}
</script>
