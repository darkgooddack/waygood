<template>
  <main>
    <div class="One">
      <div class="one-left">
        <div class="one-left-text">
          A MEETING PLACE FOR RICHMOND LOCALS
        </div>
        <div class="one-left-sub-text">
          (and everyone else)
        </div>
        <img src="/images/2.png" class="img-one">
      </div>
      <div class="one-right">
        <img src="/images/1.png">
      </div>
    </div>

    <div class="Two">
      <div class="two-left">
        <div class="two-left-text">
          GATHER IN GOOD COMPANY
        </div>
        <div class="two-left-sub-text">
          WAYGOOD is a meeting place for Richmond locals (and everyone else). We’ve taken the best parts of a bottle shop and a neighbourhood eatery and mixed them together. Drop past for a drink, stay for a bite or grab a bottle on the fly.
        </div>
        <img src="/images/3.png" class="img-two">
        <div class="two-second-text">Our only rule is: come as you are and enjoy as you please. We look forward to seeing you.</div>
      </div>
    </div>
    
    <div class="Three">
      <div class="three-left">
        <div class="three-left-text">
          BOOK YOURSELF IN
        </div>

        <div class="three-line"></div>
        
        <img src="/images/4.png" class="img-three">
      </div>
      <div class="three-right"></div>
    </div>


    <div class="Four">
      <div class="four-up">
        <div class="four-up-block-text">
          <div class="four-up-1">THE MENU</div>
          <div class="four-up-2">BELLY FULL, HEART FULL</div>
          <div class="four-up-3">Our menu changes weekly based on seasonality and inspiration, but you can always count on it being approachable and nourishing.</div>
          <div class="four-up-4">VIEW THE MENU</div>
          <div class="four-up-line"></div>
        </div>
        <div class="four-up-picture">
          <img src="/images/5.png" alt="Картинка верхнего ряда">
        </div>
      </div>

      <div class="four-down">
        <div class="four-down-picture">
          <img src="/images/6.png" alt="Картинка нижнего ряда">
        </div>
        <div class="four-down-block-text">
          <div class="four-down-1">Whether flying solo, grazing with friends or settling in for the evening, we’re certain we’ll be able to accomodate you. After all, hospitality is what we do.</div>
          <div class="four-down-2">BOOK IN</div>
          <div class="four-dowm-line"></div>
          
        </div>
      </div>
    </div>



    <div class="Five"></div>
    <div class="Six"></div>
    <div class="Seven"></div>
    <div class="Eight"></div>
    <div class="Nine"></div>
  </main>
</template>

<style scoped>
main {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
  margin: 0 auto;
  width: 100%;
}

.One {
  width: 100%; /* Занимает всю ширину, минус отступ слева */
  display: flex;
  background-color: #FAF5E5;
  justify-content: space-between; /* Размещение блоков по противоположным краям */
  
}

.one-left {
  width: 50%; /* Левый блок занимает 50% ширины */
  display: flex;
  flex-direction: column;
  justify-content: center; /* Центрирование текста */
  align-items: center;
  
  position: relative;
}


.one-left::after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 50%; /* Центрируем линию */
  transform: translateX(-50%); /* Сдвигаем линию на половину её ширины */
  width: 90%; /* Делаем линию шириной 90% от ширины родительского блока */
  height: 1px;
  background-color: black; /* Горизонтальная линия 1px */
}

.one-right {
  width: 50%; /* Правый блок также 50% */
  display: flex;
  justify-content: center; /* Центрируем картинку по горизонтали */
  align-items: center; /* Центрируем картинку по вертикали */
}

.one-left-text {
  width: 313px;
  height: auto; /* Убираем фиксированную высоту */
  font-family: Roboto;
  font-weight: 400;
  font-size: 51px;
  line-height: 58.65px;
  letter-spacing: 0%;
  text-align: center;
  color: #171717;
}

.one-left-sub-text {
  width: 179px;
  height: auto; /* Убираем фиксированную высоту */
  font-family: Roboto;
  font-weight: 400;
  font-size: 13px;
  line-height: 13px;
  letter-spacing: 2.08px;
  text-align: center;
  color: #171717;
  margin-top: 30px;
  margin-bottom: 80px;
}

.img-one {
  width: 190px;
  height: 190px;
}

.one-right img {
  width: 100%; /* Картинка растягивается по ширине правого блока */
  height: 100%; /* Растягиваем по высоте */
  object-fit: cover; /* Пропорциональное растяжение, чтобы картинка заполнила блок */
}

.Two {
  width: 100%;/* Занимает всю ширину, минус отступ слева */
  display: flex;
  background-color: #FAF5E5;
  justify-content: space-between; /* Размещение блоков по противоположным краям */
  margin-top: 90px;
}

.two-left {
  width: 50%; /* Левый блок занимает 50% ширины */
  display: flex;
  flex-direction: column;
  justify-content: center; /* Центрирование текста */
  align-items: center;
}

.two-right {
  width: 50%; /* Правый блок также 50% */
  display: flex;
  justify-content: center; /* Центрируем картинку по горизонтали */
  align-items: center; /* Центрируем картинку по вертикали */
}

.two-left-text {  
  width: 285px;
  height: auto; /* Убираем фиксированную высоту */
  font-family: Roboto;
  font-weight: 400;
  font-size: 51px;
  line-height: 58.65px;
  letter-spacing: 0%;
  text-align: center;
  color: #171717;
  margin-bottom: 40px;
}

.two-left-sub-text {
  width: 374px;
  height: auto; /* Убираем фиксированную высоту */
  font-family: Roboto;
  font-weight: 400;
  font-size: 16px;
  line-height: 22.4px;
  letter-spacing: 0.32px;
  text-align: center;
  text-align: center;
  color: #171717;
  margin-bottom: 80px;
}

.img-two {
  width: 283px;
  height: 140px;
}

.two-second-text {
  width: 339px;
  height: 136px;
  font-family: Roboto;
  font-weight: 400;
  font-size: 26px;
  line-height: 33.8px;
  letter-spacing: 0.78px;
  margin-top: 105px;
}



.Three {
  width: 100%;/* Занимает всю ширину, минус отступ слева */
  display: flex;
  background-color: #FAF5E5;
  justify-content: space-between; /* Размещение блоков по противоположным краям */
  margin-top: 80px;
}

.three-left {
  width: 50%; /* Левый блок занимает 50% ширины */
  display: flex;
  flex-direction: column;
  justify-content: center; /* Центрирование текста */
  align-items: center;
}

.three-right {  
  width: 50%; /* Правый блок также 50% */
  display: flex;
  justify-content: center; /* Центрируем картинку по горизонтали */
  align-items: center; /* Центрируем картинку по вертикали */
}


.three-left-text {
  font-family: Roboto;
  font-weight: 400;
  font-size: 13px;
  letter-spacing: 2.08px;
  text-align: center;
  color: #171717;
  margin-bottom: 5px;
}

.three-line {
  width: 100px;
  height: 1px;
  background-color: black;
  margin-bottom: 12px;
}

.img-three {
  width: 282px;
  height: 376px;
  margin-bottom: 60px;
}
.Four {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 40px; /* Отступ между рядами */
}

/* Общие стили для рядов */
.four-up {
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: flex-start; /* Верхнее выравнивание */
  margin-top: 137px;
  flex-wrap: wrap;
  
  
}

/* Блок текста в верхнем ряду */
.four-up-block-text {
  width: 50%; /* Уменьшаем ширину блока для большего пространства */
  display: flex;
  flex-direction: column;
  align-items: flex-start; /* Выровнять текст по левому краю */
  text-align: left; /* Выравнивание текста по левому краю */
  padding-left: 250px;

  
}

/* Отдельные текстовые элементы */
.four-up-1, .four-up-2, .four-up-3, .four-up-4 {
  text-align: left; /* Убираем центрирование */
}

.four-up-1 {
  font-family: Roboto;
  font-weight: 400;
  font-size: 13px;
  letter-spacing: 2.08px;
}

.four-up-2 {
  width: 500px;

  font-family: Roboto;
font-weight: 400;
font-size: 59px;
line-height: 63px;
letter-spacing: 1.8px;

  margin-top: 48px;
}

.four-up-3 {
  width: 320px;

  font-family: Roboto;
  font-weight: 400;
  font-size: 16px;
  line-height: 22.4px;
  letter-spacing: 0.32px;


  margin-top: 52px;
}

.four-up-4 {
  font-family: Roboto;
  font-weight: 400;
  font-size: 13px;
  letter-spacing: 2.08px;

  margin-top: 34px;
}

/* Линия под текстом */
.four-up-line {
  width: 123px;
  height: 1px;
  background: #0000004D;
  margin-top: 5px;
}

/* Блоки с изображениями */
.four-up-picture img, .four-down-picture img {
  width: 100%;
  max-width: 404px; /* Ограничиваем размер изображений */
  height: auto; /* Автоматическая высота */
  object-fit: cover;
}

.four-up-picture {
  text-align: left;
  padding-right: 250px;
  align-self: flex-end;
}




.four-down {
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap; /* Разрешаем перенос элементов */
}

/* Нижний блок текста (по центру) */
.four-down-block-text {
  display: flex;
  flex-direction: column;
  align-items: flex-start; /* Прижимает содержимое к левому краю */
  text-align: left; /* Убирает центрирование текста */
  max-width: 404px;
  margin-top: 154px;
  margin-bottom: 181px;
  margin-right: 250px; /* Если не нужно, уберите */
}


.four-down-1 {
  width: 390px;
  height: 203px;
  font-family: Roboto;
  font-weight: 400;
  font-size: 26px;
  line-height: 33.8px;
  letter-spacing: 0.78px;
  text-align: left;
}

.four-down-2 {
  width: 70px;
  font-family: Roboto;
  font-weight: 400;
  font-size: 13px;
  line-height: 13px;
  letter-spacing: 2.08px;
  text-align: left;

}
.four-down-picture{
  padding-left: 250px;
}

.four-dowm-line {
  width: 70px;
  height: 1px;
  background: #0000004D;
  margin-top: 5px;
}

.Five, .Six, .Seven, .Eight, .Nine {
  width: 100%;
}
</style>
