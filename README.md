# waygood
Сайт ресторана

my-vue-app/
│── public/           # Статические файлы (favicon, картинки)
│   ├── favicon.ico
│   ├── images/
│── src/              # Основной код проекта
│   ├── assets/       # Медиафайлы (если нужны)
│   ├── components/   # Повторно используемые компоненты
│   │   ├── Header.vue
│   │   ├── HeroSection.vue
│   │   ├── Features.vue
│   │   ├── Footer.vue
│   ├── pages/        # Можно не создавать, если вся логика в `App.vue`
│   ├── App.vue       # Главный компонент (вся страница здесь)
│   ├── main.js       # Входная точка приложения
│   ├── style.css     # Глобальные стили
│── index.html        # Основной HTML-файл
│── package.json      # Зависимости и скрипты
│── vite.config.js    # Конфигурация Vite
│── README.md         # Документация проекта
