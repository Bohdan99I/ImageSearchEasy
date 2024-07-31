# ISE (ImageSearchEasy)

**ISE** - це веб-застосунок для пошуку та перегляду зображень за ключовими
словами. Він використовує публічний API сервісу Pixabay для отримання зображень.
Застосунок надає зручний інтерфейс для користувачів та підтримує багато корисних
функцій.

## Функціональність

- **Пошук зображень**: Можливість шукати зображення за ключовими словами.
- **Повідомлення**: Використання бібліотеки Notiflix для відображення
  повідомлень користувачам.
- **Перегляд зображень**: Відображення великої версії зображень за допомогою
  бібліотеки SimpleLightbox.
- **Нескінченне завантаження**: Автоматичне завантаження нових зображень під час
  прокручування сторінки.

## Використані технології

- **axios**: Для здійснення HTTP-запитів до API Pixabay.
- **async/await**: Для зручної роботи з асинхронними операціями.
- **Notiflix**: Для відображення повідомлень користувачам.
- **SimpleLightbox**: Для перегляду великої версії зображень.

## Використання

1. **Пошук зображень**:

   - Введіть ключове слово у пошуковий рядок.
   - Натисніть кнопку пошуку.
   - Застосунок виконає запит до API Pixabay та відобразить знайдені зображення.

2. **Перегляд зображень**:

   - Клікніть на будь-яке зображення для перегляду його у великому розмірі з
     використанням SimpleLightbox.

3. **Нескінченне завантаження**:
   - Прокрутіть сторінку вниз, щоб автоматично завантажити додаткові зображення.

## Як користуватися

1. **Клонуйте репозиторій**:
   ```bash
   git clone https://github.com/Bohdan99I/ISE.git
   ```
2. **Перейдіть у директорію проекту**:
   ```bash
   cd ImageSearchEasy
   ```
3. **Встановіть залежності**:
   ```bash
   npm install
   ```
4. **Запустіть застосунок**:
   ```bash
   npm start
   ```

## Посилання на застосунок

- Ознайомитися із продуктом можна на [на сайті]
  (https://github.com/Bohdan99I/ISE.git).
