## Налаштування проєкту:

```sh
git clone https://github.com/LinemediaDev/FrontendInterview.git
cd FrontendInterview
npm install
npm run dev
```
Після запуску команд має бути доступна сторінка https://localhost:3000

## З якими файлами доведеться працювати:
1) `app.js` - конфігурація [express](https://expressjs.com/en/guide/routing.html) додатку для запуску на локалі
1) `public/index.html` - HTML файл, який рендериться за посиланням https://localhost:3000
1) `public/index.css` - CSS файл, підключається в `index.html`
1) `public/index.js` - JS файл, підключається в `index.html`
1) `db.json` - містить данні про статті, які потрібно буде відобразити на сторінці

## Що треба зробити:
1) `app.js` - імплементувати роут `app.get('/items/'` який має повернути записи з файлу `db.json`
1) `public/index.js` відправити запит на роут `/items/`, отримати данні статтей та відобразити їх в елементі `.articles`
1) Налаштувати пагінацію на сторінці (кнопки "попередня" та "наступна"), показувати 5 статтей на сторінку. Використати готову верстку і стилі пагінатора

## Статті мають виглядати наступним чином:
![Articles](/final-project.png)