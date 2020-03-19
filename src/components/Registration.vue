<template>
    
<div class="container"> 
<form>
    <table align="center">

 <tr><td>UserName:</td> <td> <input type="text" name="username"></td></tr>
 <br>
 <tr><td>Password:</td><td><input type="password" name="password"/></td></tr>
 <br>
 <tr><td>Email:</td><td><input type ="email" name="email"/></td></tr><br>
 <tr><td>Address:</td><td><input type="textarea" name="address"/></td></tr><br>
  <tr><td>Mobile no:</td><td><input type="text" name="mobile" /></td></tr><br>
  <br>
 <button class="btn" >register</button>
    </table> 
</form>
    
</div>


</template>

<script>
export default {
    name:"Registration"
    
}
</script>

<style scoped>
table{
     padding: 30px;
 }
 .btn {
      color: white;
      padding: 12px 10px;
      margin: 8px 0;
      border: none;
      cursor: pointer;
      width: 100%;
      
      background-color: #4CAF50;
     
 }
 .container {
  padding: 16px;
  background-color: white;
}
 
</style>