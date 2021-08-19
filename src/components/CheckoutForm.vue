<template>
  <form>
    <div class="form-group">
      <div class="form-class">
        <label for="firstname">First name</label>
        <input type="text" name="firstname" />
      </div>

      <div class="form-class">
        <label for="lastname">Last name</label>
        <input type="text" name="lastname" />
      </div>

      <div class="form-class">
        <label for="email">Email</label>
        <input type="text" name="email" />
      </div>

      <div class="form-class">
        <label for="adress">Address</label>
        <input type="text" name="adress" />
      </div>

      <div class="form-class">
        <label for="country">Country</label>
        <input type="text" name="country" />
      </div>

      <div class="form-class">
        <label for="state">state</label>
        <input type="text" name="state" />
      </div>
    </div>
  </form>
</template>

<script>
export default {};
</script>

<style scoped>
 .form-group{
     display: flex;
     flex-wrap: wrap;
 }

 .form-class{
     flex: 40%;
     margin-right:
 }
 input{
     height: 25px;
     border-radius:5px;
     display: block;
     padding:3px;
     /* margin:15px 2rem; */
 }
</style>
