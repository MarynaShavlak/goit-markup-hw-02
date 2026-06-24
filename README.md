# goit-markup-hw-02

Навчальний проєкт у межах курсу **GoIT** — Модуль 2 «Вступ до CSS». Верстка та
базова стилізація лендингу **WebStudio** за макетом: підключення шрифтів,
кольори, типографіка та інтерактивні стани (hover / focus).

**Демо:** https://marynashavlak.github.io/goit-markup-hw-02/

## Опис

Сторінку зверстано за макетом із дотриманням семантики HTML та оформлено за
допомогою CSS. Складається з таких блоків:

- **Header** — логотип `WebStudio` (акцентна частина «Web» виділена через
  `<span>`), навігація (`Features`, `Team`, `Portfolio`) та контакти
- **Hero** — заголовок «Effective Solutions for Your Business» і кнопка
  `Order Service`
- **Features** — чотири переваги компанії: Strategy, Punctuality, Diligence,
  Technologies
- **Our Team** — картки членів команди з фото та посадами
- **Our Portfolio** — шість проєктів із зображеннями та категоріями
- **Footer** — логотип `WebStudio` і короткий опис компанії

## Технології

- HTML5 (семантична розмітка)
- CSS3 — шрифти, кольори, типографіка, стани `:hover` / `:focus`
- [modern-normalize](https://github.com/sindresorhus/modern-normalize) —
  нормалізація стилів
- [Google Fonts](https://fonts.google.com/) — `Roboto` та `Raleway`
- [Prettier](https://prettier.io/) — форматування коду

## Організація стилів

У `index.html` підключається лише `css/main.css`, який імпортує решту файлів у
визначеному порядку:

```
@import './common.css';
@import './header.css';
@import './hero.css';
@import './features.css';
@import './team.css';
@import './portfolio.css';
@import './footer.css';
```

Глобальні та базові стилі описані в `common.css`, стилі конкретних блоків — у
відповідних файлах.

## Структура

```
goit-markup-hw-02/
├── css/
│   ├── common.css
│   ├── features.css
│   ├── footer.css
│   ├── header.css
│   ├── hero.css
│   ├── main.css
│   ├── portfolio.css
│   └── team.css
├── images/
│   ├── portfolio-1.jpg … portfolio-6.jpg
│   └── team-1.jpg … team-4.jpg
├── .gitignore
├── .prettierrc
├── index.html
└── README.md
```
