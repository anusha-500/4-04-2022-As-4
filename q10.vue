<template>
    <div>
        <h1>Question 10</h1>
        <p>First Name:{{first_name}}</p>
        <p>Last Name{{last_name}}</p>
        <p>FullName:{{fullname}}</p>
        <button @click="namefun()" >clickme</button>
    </div>
</template>
<script>
    export default{
        name:"Q10ASS",
        data(){
            return{
                first_name: "500apps" , 
                last_name :"infinity",
                fullname:" "

            }
        },
        methods:{
            namefun(){
                this.fullname=this.first_name+this.last_name
                console.log(this.fullname);
            }

        }
    }
</script>
