<template>

</template>

<script>
import axios from "axios";
export default {
  data() {
    return {
    }

  },
  created() {
    axios. get('https://api.giphy.com/v1/gifs/trending?api_key=xWN5FetwcKhYyWXKJyEjl1Fm1ADLAftr').then((response)=>{
      console.log(response.data)
    })


  }
}
</script>

