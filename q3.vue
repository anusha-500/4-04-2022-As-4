<template>
    <div>
        <h1>Question 3</h1>
        <p>{{userdata}}</p>
        <p>{{userdata1}}</p>
        <button @click="detailfun()">clickme!</button>
        </div>
</template>
<script>
export default{
    name:"Q3AD",
    data(){
        return{
            arr:[
{"category1": [{ "name": "cat1", "description": "it is cat1", "details": ["name", "category", "age", "contact"]
}]
},{"category2": [{ "name": "cat2", "description": "it is cat2", "details": ["name2", "category2", "age2", "contact2"]
}]
}
],
userdata:" ",
userdata1:" "
        }
    },
    methods:{
        detailfun(){
            this.userdata=this.arr[0].category1[0].details;
            this.userdata1=this.arr[1].category2[0].details;
            console.log(this.userdata);
            console.log(this.userdata1);

        }
    }
}
</script>
