<template>
  <footer>
    <div class="footer-left">
      <img src="/images/footer.png" class="footer-img" alt="Logo">
    </div>
    <div class="footer-line"></div>
    <div class="footer-right">
      <div class="footer-right-up">
        <div class="footer-column">Column 1</div>
        <div class="footer-column">Column 2</div>
        <div class="footer-column">Column 3</div>
      </div>
      
      <div class="footer-line-h"></div> <!-- Горизонтальная линия -->

      <div class="footer-right-down">
        <div class="footer-column">© 2022 WAYGOOD</div>
        <div class="footer-column">WORDS BY MIA BARRY</div>
        <div class="footer-column">PHOTOGRAPHY BY KRIS PAULSEN</div>
        <div class="footer-column">DESIGN BY AFTER HOURS STUDIO</div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
footer {
  width: 100%;
  height: 240px;
  background-color: #FFD36B;
  color: black;
  display: flex;
  justify-content: space-between;
  align-items: stretch;
}

.footer-left {
  width: 30%; /* Задаем 30% ширины для левой части */
  display: flex; /* Включаем Flexbox */
  justify-content: center; /* Центрируем по горизонтали */
  align-items: center; /* Центрируем по вертикали */
}

.footer-img {
  width: 180px;
  height: 180px;
}


.footer-line {
  width: 1px;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.8);
}

.footer-right {
  width: 70%; /* Задаем 70% ширины для правой части */
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  height: 100%; /* Это необходимо для правильного распределения высоты между верхним и нижним блоками */
}

.footer-right-up {
  height: 85%; /* Верхний блок занимает 90% высоты */
  display: flex;
  justify-content: space-between;
}

.footer-right-down {
  height: 15%; /* Нижний блок занимает 10% высоты */
  display: flex;
  justify-content: space-between;
}

.footer-column {
  width: 30%; /* Можно изменить на нужную ширину для столбцов */
  text-align: center; /* Горизонтальное выравнивание текста */
  display: flex; /* Используем flex для выравнивания */
  justify-content: center; /* Центрируем текст по горизонтали */
  align-items: center; /* Центрируем текст по вертикали */
  height: 100%; /* Это важно, чтобы столбцы растягивались по высоте */
  font-family: Roboto;
  font-weight: 400;
  font-size: 9px;
}

.footer-right-up {
  margin-bottom: 10px; /* Отступ между верхним и нижним рядами */
}

.footer-right-down .footer-column {
  width: 23%; /* Подгоняем под 4 столбца */
}

/* Горизонтальная линия между верхним и нижним блоками */
.footer-line-h {
  height: 1px; /* Высота линии */
  background-color: rgba(0, 0, 0, 0.8);}
</style>
