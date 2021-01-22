<template>

  <div class="main" >
  <h1>Enter your credit card information</h1>
  <div class='main'>
    <div class='one'>
    <input type="input" placeholder="Card Name" class="number" style='margin-bottom: 10px;'>
    <input type="number" placeholder="Card Number" class="number">
    </div>
    <div class='number'>
    <input type="date">
    <input type="number" placeholder="CVV/CVC" style='margin-left: 10px;'>
    </div>
  </div>
   </div>

</template>
<style lang="css" scoped>

.main{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-bottom: 10px;


}
.one{
    display: flex;
    flex-direction: column;
    width: 300px;
    padding-bottom: 10px;

}
.number{
    display: flex;
    flex-direction: row;
    width: 300px;
}
input {
  outline: 0;
  border-width: 0 0 2px;
  border-color: purple;
  border-radius: 2px;
}
input:focus {
  border-color: green
}

</style>
