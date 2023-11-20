<script setup lang="ts">

</script>

<template>
  <div class="main">
<!--    -->
    <img class="red-light" src="../public/red%20light.svg" alt="red-light">
    <img class="red-ball" src="../public/red%20ball.svg" alt="red-ball">
    <img class="purple-light" src="../public/purple%20light.svg" alt="purple-light">
    <img class="purple-ball" src="../public/purple%20ball.svg" alt="purple-ball">
    <img class="red-ball-small" src="../public/red%20ball%20small.svg" alt="red-ball-small">
        <!--  header  -->
    <header class="header">
      <div class="container">
        <div class="header-box">
          <div class="logo">
            <img src="../public/logo_welbex.svg" alt="logo">
            <p class="description description--small">крупный интегратор CRM в Росcии и ещё 8 странах</p>
          </div>
          <ul class="menu">
            <li class="menu__item"><a class="link" href="#">Услуги</a></li>
            <li class="menu__item"><a class="link" href="#">Виджеты</a></li>
            <li class="menu__item"><a class="link" href="#">Интеграции</a></li>
            <li class="menu__item"><a class="link" href="#">Кейсы</a></li>
            <li class="menu__item none"><a class="link" href="#">Сертификаты</a></li>
          </ul>
          <ul class="social social--none">
            <li class="social__item"><a class="link" href="tel:+75555555555">+7 555 555-55-55</a></li>
            <li class="social__item"><a href="tel:+75555555555"><img src="../public/telegram.svg" alt="telegram-img"></a></li>
            <li class="social__item"><a href="tel:+75555555555"><img src="../public/viber.svg" alt="viber-img"></a></li>
            <li class="social__item"><a href="tel:+75555555555"><img src="../public/whatsapp.svg" alt="whatsapp-img"></a></li>
          </ul>
        </div>
      </div>
    </header>
        <!--  banner  -->
    <section class="banner">
      <div class="container">
        <div class="banner-box">
          <div class="banner-block block1">
            <h1 class="caption caption--big">Зарабатывайте больше</h1>
            <span class="text text--big">с WELBEX</span>
            <p class="description description--big">Развиваем и контролируем продажи за вас</p>
          </div>
          <div class="banner-block block2">
            <div class="row">
              <div class="col-1">
                <h3 class="caption caption--small">Вместе с <span class="text">бесплатной </span><span class="text">консультацией</span> мы дарим:</h3>
              </div>
              <div class="row">
                <div class="col-2">
                  <h3 class="caption">Виджеты</h3>
                  <p class="description">30 готовых решений</p>
                </div>
                <div class="col-2">
                  <h3 class="caption">Dashboard</h3>
                  <p class="description">с показателями
                    вашего бизнеса</p>
                </div>
              </div>
              <div class="row">
                <div class="col-2">
                  <h3 class="caption">Skype Аудит</h3>
                  <p class="description">отдела продаж и CRM системы</p>
                </div>
                <div class="col-2">
                  <h3 class="caption">35 дней</h3>
                  <p class="description">использования CRM</p>
                </div>
              </div>
              <button class="btn">Получить консультацию</button>
            </div>
          </div>
          <div class="block3">
            <div style="display: flex; flex-direction: column;">
              <h1><div class="line"></div>Skype аудит</h1>
              <h1><div class="line"></div>Dashboard</h1>
            </div>
            <div style="display: flex; flex-direction: column;">
              <h1><div class="line"></div>30 виджетов</h1>
              <h1><div class="line"></div>Месяц аmoCRM</h1>
            </div>
          </div>
        </div>
      </div>
    </section>
        <!--  footer  -->
    <footer class="footer">
      <div class="container">
        <div class="footer-box">
          <div class="footer-services">
            <div class="service-item">
              <h2 class="footer-caption">О компании</h2>
              <ul class="menu-service">
                <li class="menu-serice__item"><p class="footer-service-link"><a class="footer-link" href="#">Партнёрская программа</a></p></li>
                <li class="menu-serice__item"><p class="footer-service-link"><a class="footer-link" href="#">Вакансии</a></p></li>
              </ul>
            </div>
            <div class="service-item">
              <h2 class="footer-caption">Меню</h2>
              <ul class="menu-service">
                <li class="menu-service__item"><p class="footer-service-link"><a class="footer-link" href="#">Расчёт стоимости</a></p></li>
                <li class="menu-service__item"><p class="footer-service-link"><a class="footer-link" href="#">Услуги</a></p></li>
                <li class="menu-service__item"><p class="footer-service-link"><a class="footer-link" href="#">Виджеты</a></p></li>
                <li class="menu-service__item"><p class="footer-service-link"><a class="footer-link" href="#">Интеграции</a></p></li>
                <li class="menu-service__item"><p class="footer-service-link"><a class="footer-link" href="#">Наши клиенты</a></p></li>
              </ul>
            </div>
            <div class="service-item">
              <h2></h2>
              <ul class="menu-service">
                <li class="menu-service__item"><p class="footer-service-link"><a class="footer-link" href="#">Кейсы</a></p></li>
                <li class="menu-service__item"><p class="footer-service-link"><a class="footer-link" href="#">Благодарственные письма</a></p></li>
                <li class="menu-service__item"><p class="footer-service-link"><a class="footer-link" href="#">Сертификаты</a></p></li>
                <li class="menu-service__item"><p class="footer-service-link"><a class="footer-link" href="#">Блог на Youtube</a></p></li>
                <li class="menu-service__item"><p class="footer-service-link"><a class="footer-link" href="#">Вопрос / Ответ</a></p></li>
              </ul>
            </div>
          </div>
          <div class="footer-social">
            <h2 class="footer-caption">Контакты</h2>
            <p style="margin-top: 20px;"><a class="link" href="tel:+75555555555">+7 555 555-55-55</a></p>
            <ul class="social social--spacing">
              <li class="social__item"><a href="tel:+75555555555"><img src="../public/telegram.svg" alt="telegram-img"></a></li>
              <li class="social__item"><a href="tel:+75555555555"><img src="../public/viber.svg" alt="viber-img"></a></li>
              <li class="social__item"><a href="tel:+75555555555"><img src="../public/whatsapp.svg" alt="whatsapp-img"></a></li>
            </ul>
            <p class="description location">Москва, Путевой проезд 3с1, к 902</p>
          </div>
        </div>
        <div style="text-align: right; margin-top: 33px;">
          <p class="description description--footer">©WELBEX 2022. Все права защищены.</p>
          <a class="description description--footer" href="#"><p>Политика конфиденциальности</p></a>
        </div>
      </div>
    </footer>
  </div>
</template>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
.main{
  position: relative;
}
.red-light{
  width: 300px;
  position: absolute;
  top: 20%;
  left: 0;
}
.red-ball{
  position: absolute;
  top: 50px;
  left: 40%;
}
.purple-light{
  width: 400px;
  position: absolute;
  top: 0;
  left: 40%;
}
.purple-ball{
  position: absolute;
  left: 60%;
}
.red-ball-small{
  position: absolute;
  top: 60%;
  left: 60%;
}
.none{
  display: block;
}
.social--none{
  display: block;
}

.header-box{
  display: flex;
  justify-content: space-between;
  align-items: start;
  padding: 46px 0;
}
.logo{
  width: 150px;
}

.menu{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  gap: 30px;
}
.link{
  color: #E4E5EA;
  font-family: 'Inter';
  font-size: 16px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
}

.social{
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 30px;
}
.banner{
  padding-bottom: 69px;
}
.banner-box{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.banner-block{
  width: 50%;
}
.block2{
  display: flex;
  justify-content: right;
  text-align: right;
  width: 291px;
}

.row{
  display: flex;
  justify-content: right;
  flex-wrap: wrap;
  width: 100%;
}
.col-1{
  width: 100%;
  margin-bottom: 40px;
}
.col-2{
  width: 50%;
  margin-bottom: 30px;
}
.text{
  background: linear-gradient(90deg, #FCB045 36.99%, #FD1D1D 100%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-family: 'Inter';
  font-size: 18px;
  font-style: normal;
  font-weight: 700;
  line-height: normal;
  letter-spacing: 0.9px;
  text-transform: uppercase;
}
.text--big{
  font-size: 48px;
  font-style: normal;
  font-weight: 900;
  line-height: normal;
  margin: 0;
  padding: 0;
}

.caption{
  color: #E4E5EA;
  text-align: right;
  font-family: 'Inter';
  font-size: 18px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  letter-spacing: 0.9px;
  text-transform: uppercase;
  margin-top: 0;
  margin-bottom: 6px;
}
.caption--big{
  font-size: 48px;
  font-weight: 400;
  text-align: start;
  text-transform: inherit;
  margin: 0;
  padding: 0;
}
.caption--small{
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  text-transform: inherit;
}

.description {
  color: #E4E5EA;
  text-align: right;
  font-family: 'Montserrat';
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}
.description--big {
  width: 275px;
  font-size: 18px;
  text-align: start;
  margin-top: 30px;
}
.description--small{
  font-size: 10px;
  font-weight: 300;
  text-align: start;
}

.btn{
  background: #4077F3;
  color: #E4E5EA;
  font-family: 'Inter';
  font-size: 16px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  padding: 21px 34px;
  border-radius: 0;
}

.footer{
  padding: 10px 0;
}

.footer-box{
  display: flex;
}
.footer-services{
  display: flex;
  flex-wrap: wrap;
  width: 70%;
}
.service-item{
  width: 33.3333%;
}
.footer-caption{
  color:  #656566;
  font-family: 'Inter';
  font-size: 14px;
  font-style: normal;
  font-weight: 700;
  line-height: normal;
  letter-spacing: 0.7px;
  text-transform: uppercase;
}
.menu-service{
  display: flex;
  flex-direction: column;
}
.footer-link{
  color: #E4E5EA;
  font-family: 'Inter';
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}
.footer-social{
  display: flex;
  flex-direction: column;
  align-items: end;
}
.location{
  font-family: 'Inter';
  font-weight: 400;
}
.social--spacing{
  margin: 20px 0;
}
.description--footer{
  font-family: 'Montserrat';
  font-size: 12px;
}
.block3{
  display: none;
}
.block3 div:nth-child(1){
  margin-right: 10px;
}
.block3  h1{
  color: #E4E5EA;
  font-family: 'Montserrat';
  font-size: 13px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  letter-spacing: 0.65px;
  text-transform: uppercase;
  display: flex;
  align-items: center;
}
.line{
  width: 10px;
  height: 1px;
  background: linear-gradient(90deg, #FCB045 36.99%, #FD1D1D 100%);
}

@media (max-width: 992px) {
  .social--none{
    display: none;
  }
}
@media (max-width: 768px) {
  .logo{
    display: none;
  }
  .menu{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    width: 100%;
    gap: 0;
  }
  .banner-block{
    width: 100%;
  }
  .row{
    justify-content: start;
  }
  .caption{
    text-align: start;
  }
  .description{
    text-align: start;
  }
  .footer-box{
    flex-wrap: wrap;
    flex-direction: column;
  }
  .footer-services{
    width: 100%;
  }
  .footer-social{
    align-items: start;
  }
}
@media (max-width: 572px) {
  .banner{
    background-image: url("../public/bg.png");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    padding-top: 40px;
  }
  .none{
    display: none;
  }
  .link{
    font-size: 12px;
  }
  .block2{
    display: none;
  }
  .caption--big{
    font-size: 36px;
  }
  .text--big{
    font-size: 36px;
  }
  .description--big{
    font-size: 18px;
    margin-bottom: 20px;
  }
  .service-item{
    width: 50%;
  }
  .service-item:first-child{
    width: 100%;
    margin-bottom: 23px;
  }
  .social--spacing{
    margin: 8px 0;
  }
  .footer-social{
    margin-top: 20px;
  }
  .footer-service-link{
    font-size: 14px;
  }
  .block3{
    display: flex;
  }
  .header-box{
    padding: 20px 0;
  }
}
@media (max-width: 414px) {
  .service-item{
    width: 100%;
  }
  .red-ball-small, .red-ball, .purple-ball, .purple-light, .red-light{
    display: none;
  }


}
</style>
