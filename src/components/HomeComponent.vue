<template>
  <div>
    <h1>Email {{email}}</h1>
    <h1>Mobile{{mobile}}</h1>

    <button v-on:click="getdata('button clicked')">click me</button>
  </div>
     
</template>

<script>
export default {
  name: 'HomeComponent',
  data(){
   
        return{email: "geeta@gmail.com",
        mobile:  13563}
   
    },
    methods:{
        getdata(data){
        alert (data);
        }
    }
  
 
}
</script>