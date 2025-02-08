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
    
    <div class="Three"></div>
    <div class="Four"></div>
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
  width: 100%;
}















.Four, .Five, .Six, .Seven, .Eight, .Nine {
  width: 100%;
}
</style>
