<template>
  <div class="hello">
    <div class="screen1">
      <nav class="container-fluid desktopNav">
        <div class="row">
          <div class="col-12 logo"><span class="logofont">T</span>Bot</div>
          <div class="col-6 d-flex align-items-center">
            <ol class="h5 ml-5">
              <!-- <li class="mx-3"><a class="text-dark" href="#">О боте</a></li> -->
              <!-- <li class="mx-3"><a class="text-dark" href="#">Функционал</a></li> -->
              <!-- <li class="mx-3"><a class="text-dark" href="#">Как создать</a></li>
              <li class="mx-3"><a class="text-dark" href="#">Стоимость</a></li> -->
            </ol>
          </div>
          <div class="col-3">
            <!-- <a class="btn btn-primary mt-4" href="">Попробовать бота</a> -->
          </div>
        </div>
      </nav>
      <div class="attentionAttractor container">
        <div class="row">
        <div class="col-12 col-md-6 text-left-block">
          <h1 class="main-header text-left font-weight-bold">Автоматизируйте продажи и консультации для клиентов</h1>
          <h3 class="text-left my-4 font-weight-normal">С помощью Telegram бота, который: </h3>
          <h4 class="text-left mx-3 my-3 font-weight-light h5">- Работает 24/7</h4>
          <h4 class="text-left mx-3 my-3 font-weight-light h5">- Отвечает, когда Ваши консультанты заняты</h4>
          <h4 class="text-left mx-3 my-3 font-weight-light h5">- Способен предварительно обработать и поставить вам готового клиента</h4>
          <h4 class="text-left mx-3 my-3 font-weight-light h5">- Может отправлять рассылки об акциях, событиях или статусах в любое удобное время</h4>
          <h4 class="text-left mx-3 my-3 font-weight-light h5">- Собирать подробную аналитику о действиях клиента</h4>
          <a class="btn btn-primary btn-lg h3 mt-2 w-75" href="">Запустить Демо</a>

        </div>
        <div class="col-0 col-md-6 chat-image-block">
          <img class="chat-image mt-5" src="../assets/img/screen.png" alt="screen">
          
        </div>
        </div>
      </div>
    </div>
    <!-- <div class="screen-2">
      <div>
        <h1 class="pt-5">Бот умеет:</h1>
        <div class="row mt-5">
          <div class="col-6">
            <img class="col-2 mx-auto" src="../assets/img/bot.svg" alt="bot 24/7">
            <h2 class='h3 mt-3'>Отвечать на вопросы 24/7</h2>
            <p class="mt-3 col-8 mx-auto">Бот будет обрабатывать запросы клиентов и подводить их ближе к продаже, даже когда вы недоступны.</p>
          </div>
          <div class="col-6">
            <img class="col-2 mx-auto" src="../assets/img/notification.svg" alt="bot 24/7">
            <h2 class='h3 mt-3'>Отправлять рассылки клиентам</h2>
            <p class="mt-3 col-8 mx-auto">Уведомляйте ваших клиентов об акциях, событиях или статусах в любое удобное для вас время.</p>
          </div>
        </div>
        <div class="row mt-5">
          <div class="col-6">
            <img class="col-2 mx-auto" src="../assets/img/analytics.svg" alt="bot 24/7">
            <h2 class='h3 mt-3'>Собирать аналитику о клиенте</h2>
            <p class="mt-3 col-8 mx-auto">Вы сможете узнать на какой стадии находится клиент, что ему интересно, просмотреть историю переписки.</p>
          </div>
          <div class="col-6">
            <img class="col-2 mx-auto" src="../assets/img/bot.svg" alt="bot 24/7">
            <h2 class='h3 mt-3'>Отвечать на вопросы 24/7</h2>
            <p class="mt-3 col-8 mx-auto">Бот будет обрабатывать запросы клиентов и подводить их ближе к продаже, даже когда вы недоступны.</p>
          </div>
        </div>
      </div>
    </div> -->

    <div class="footer">
      <p class="text-align-center footertext text-white h6">© 2018 TBot</p>
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
  font-size: 3.5rem;
  font-style: italic;
}
.logofont {
  font-family: 'Orbitron', sans-serif;
  font-weight: 900;
  color: #0088cc;
  font-size: 5rem;
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
  height: 90vh;
}

.chat-image {
  width: 20rem;
}

.desktopNav {
  height:10vh;
  /* border-bottom: 1px solid rgba(52, 58, 64, 0.5); */
}

.main-header {
  margin-top: 5rem;
}

.screen-2 {
  height: 500px;
  background-color: rgba(241, 241, 241, 0.5);
}

.footer {
  height: 10vh;
  background: #005884;
}

.footertext {
  padding-top: 4vh;
}

@media (max-width: 1024px) {
  .chat-image {
  width: 30rem;
}
  .main-header {
  margin-top: 12rem;
}
}

@media (max-width: 768px) {
  .chat-image-block {
    display: none;
  }
  .main-header {
    margin-top: 3rem;
  }
  .logo {
    font-size: 3rem;
  }
  .logofont {
    font-size: 4rem;
  }
  .main-header {
    font-size: 2rem;
  }
  .screen1 {
    height: auto;
    background-image: url(../assets/img/screen.png);
    background-size: contain;
    background-repeat: no-repeat;
    background-blend-mode: overlay;
    background-position: 150px 140px;
    background-color: rgba(255, 255, 255, 0.8);
  }
  .text-left {
    text-shadow: 0px 0px 1px rgba(0, 0, 0, 0.5);
  }
  .text-left-block {
    margin: 0 auto;
    
  }
}

</style>
