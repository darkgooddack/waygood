<template>
    <header>
      <div class="header-container">
        <div class="logo">WAYGOOD</div>
        <nav>
          <ul>
            <li><a href="#">HOME</a></li>
            <li><a href="#">ABOUT</a></li>
            <li><a href="#">MENU</a></li>
            <li><a href="#">FEED ME MENU</a></li>
            <li><a href="#">Contact Us</a></li>
            <li><a href="#">GIFT VOUCHERS</a></li>
            <li><a href="#">BOOKINGS</a></li>
          </ul>
        </nav>
      </div>
    </header>
  </template>
  
  <style scoped>
  header {
    width: 100%;
    height: 60px;
    background-color: #FAF5E5;
    display: flex;
    justify-content: center; /* Центрирование по горизонтали */
    align-items: center; /* Центрирование по вертикали */
  }
  
  .header-container {
    width: 80%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .logo {
    font-family: Roboto, sans-serif;
    font-weight: 700;
    font-size: 32px;
    color: rgb(0, 0, 0);
  }
  
  nav {
    font-family: Roboto, sans-serif;
    font-weight: 400;
    font-size: 11px;
    display: flex;
    justify-content: center; /* Центрирование по горизонтали */
    align-items: center;
  }
  
  nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: space-between;
    gap: 20px;
  }
  
  nav ul li {
    display: inline;
    display: flex; /* Добавлено для вертикального центрирования */
    align-items: center; /* Центрируем по вертикали */
  }
  
  nav ul li a {
    color: rgb(0, 0, 0);
    text-decoration: none;
    text-transform: uppercase;
    letter-spacing: 1px;
  }
  
  nav ul li a:hover {
    text-decoration: underline;
  }
  </style>
  