<template>  
  <form>
    <div id="emailHelp" class="form-text">Acesse o fantástico mundo dos Cookies</div>
    <div class="mb-3">
      <label for="exampleInputEmail1" class="form-label">E-mail </label>
      <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
    </div>
    <div class="mb-3">
      <label for="exampleInputPassword1" class="form-label">Senha </label>
      <input type="password" class="form-control" id="exampleInputPassword1">
    </div>
    <div class="mb-4 form-check">
      <input type="checkbox" class="form-check-input" id="exampleCheck1">
      <label class="form-check-label" for="exampleCheck1"> News?</label>
    </div>
    <button type="submit" class="btn btn-primary">Entre</button>
  </form>
</template>

<style scoped>
.form-text{
  margin: 40px 0 10px;
  font-weight: bolder;
}
.mb-3{
  margin: 5px 0 0;
}
.mb-4{
  margin: 10px 0px 5px;
}
button{
  margin: 10px 0 0;
}
</style>