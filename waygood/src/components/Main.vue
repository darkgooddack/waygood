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
    
    <div class="Two"></div>
    
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
  width: calc(100% - 40px); /* Занимает всю ширину, минус отступ слева */
  display: flex;
  height: 900px;
  background-color: #FAF5E5;
  margin-left: 40px; /* Отступ слева */
  justify-content: space-between; /* Размещение блоков по противоположным краям */
}

.one-left {
  width: 50%; /* Левый блок занимает 50% ширины */
  display: flex;
  flex-direction: column;
  justify-content: center; /* Центрирование текста */
  align-items: center;
}

.one-right {
  width: 50%; /* Правый блок также 50% */
  display: flex;
  justify-content: center; /* Центрируем картинку по горизонтали */
  align-items: center; /* Центрируем картинку по вертикали */
}

.one-left-text {
  width: 313px;
  height: 235px;
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
  height: 13px;
  font-family: Roboto;
  font-weight: 400;
  font-size: 13px;
  line-height: 13px;
  letter-spacing: 2.08px;
  text-align: center;
  color: #171717;
  margin-top: 30px;
  margin-bottom: 50px;
}

.one-left-image {
  width: 680px; /* Картинка по ширине 680px */
  height: auto; /* Пропорции сохраняются */
}

.one-left .one-left-sub-text {
  margin-bottom: 60px; /* Отступ от текста до картинки */
}

.one-left {
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
  height: 900px;
}

.Three {
  height: 400px;
}

.Four {
  height: 1290px;
  background-color: #9C421F;
}

.Five {
  height: 800px;
}

.Six {
  height: 600px;
}

.Seven {
  height: 500px;
}

.Eight {
  height: 850px;
}

.Nine {
  height: 650px;
}
</style>
