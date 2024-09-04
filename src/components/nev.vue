<template lang="">
    <div>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#news">News</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#about">About</a></li>
        </ul>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Kanit&display=swap');
*{
    box-sizing: border-box;
    font-family: 'Kanit', sans-serif;
    text-align: center;
}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #a6cbee;
  padding-right: 25px;
}
li {
  float: right;
}
li a {
  display: block;
  color: white;
  font-weight: bold;
  text-align: center;
  padding: 30px 16px;
  font-size: 120%;
  text-decoration: none;
}
li a:hover {
  background-color: #8d95d4;
}
</style>