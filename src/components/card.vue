<template lang="">
    <div>
        <div class="card">
            <img :src="image" alt="pic" style="width:40%">
              <div class="container">
                <h2><b>{{ name }}</b></h2>
                <p>{{ detail }}</p>
                <br>
                <p>{{ location }}</p>
              </div>
        </div>
    </div>
</template>

<script>
export default {
    props: ['name','detail','location','image']
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Kanit&display=swap');
*{
    box-sizing: border-box;
    font-family: 'Kanit', sans-serif;
    background-color: rgb(255, 255, 255);
}
.card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  width: 80%;
  padding: 15px 15px 15px 15px;
  margin-bottom: 20px;
  margin-left: 150px;
  display: flex;
  border-radius: 15px;
}
.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}
.container {
  padding: 2px 50px;
  display: block;
  margin: auto;
}
h2 {
    padding-bottom: 20px;
}
</style>