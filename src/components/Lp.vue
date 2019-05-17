<template>
  <div class="hello">
    <div class="screen1">
      <nav class="container-fluid desktopNav">
        <div class="row">
          <div class="col-3 logo"><span class="logofont">T</span>Bot</div>
          <div class="col-6 d-flex align-items-center">
            <ol class="h5 ml-5">
              <li class="mx-3"><a class="text-dark" href="#">О боте</a></li>
              <li class="mx-3"><a class="text-dark" href="#">Функционал</a></li>
              <li class="mx-3"><a class="text-dark" href="#">Как создать</a></li>
              <li class="mx-3"><a class="text-dark" href="#">Цена</a></li>
            </ol>
          </div>
          <div class="col-3">
            <a class="btn btn-primary mt-4" href="">Попробовать бота</a>
          </div>
        </div>
      </nav>
      <div class="attentionAttractor container">
        <div class="row">
        <div class="col-6">
          <h1 class="main-header text-left font-weight-bold">Автоматизируйте продажи и консультации для клиентов</h1>
          <h3 class="text-left my-3 font-weight-normal">С помощью Telegram бота, который: </h3>
          <h4 class="text-left mx-3 my-3 font-weight-light">- Работает 24/7</h4>
          <h4 class="text-left mx-3 my-3 font-weight-light">- Отвечает, когда Ваши консультанты заняты</h4>
          <h4 class="text-left mx-3 my-3 font-weight-light">- Способен предварительно обработать и поставить вам готового клиента</h4>
          <a class="btn btn-primary btn-lg" href="">Демо версия бота</a>

        </div>
        <div class="col-6">
          <img class="chat-image mt-5" src="../assets/img/screen.svg" alt="screen">
          
        </div>
        </div>
      </div>
    </div>
    <div class="screen-2">

    </div>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

@import url('https://fonts.googleapis.com/css?family=Orbitron:400,500,700,900&display=swap');

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  transition: 0.3s;
  color: #42b983;
}
.logo {
  font-size: 3rem;
  font-style: italic;
}
.logofont {
  font-family: 'Orbitron', sans-serif;
  font-weight: 900;
  color: #0088cc;
  font-size: 4rem;
  position: relative;
  left: 1rem;
  
}

.btn-primary {
  background-color: #0088cc;
  color: #fff;
  
}

.btn-primary:hover {
  background-color: #0088cc;
  opacity: 0.9;
  
}

.text-primary {
  color: #000;

}

.text-primary:hover {
  color: #000;
}

.screen1 {
  height: 700px;
}

.chat-image {
  width: 20rem;
}

.desktopNav {
  border-bottom: 1px solid rgba(52, 58, 64, 0.5);
}

.main-header {
  margin-top: 10rem;
}

.screen-2 {
  height: 500px;
  background-color: rgba(222, 222, 222, 0.5);
}

</style>
