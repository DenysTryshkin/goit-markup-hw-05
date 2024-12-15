# Homework: Topic 4. Decorative Effects. Animation

## Assignment Instructions

### Preparation
1. **Create a new repository** with the name `goit-markup-hw-04`.
2. **Clone the repository** to your local computer.
3. **Copy files from the previous assignment** into the new repository.
4. Add markup and styles according to the requirements of this assignment.

### Working with SVG
1. **Generate the SVG sprite**:
   - Use the [Icomoon](https://icomoon.io/) service to create the SVG sprite.
2. **Optimize the SVG sprite**:
   - Use the [SVGOMG](https://jakearchibald.github.io/svgomg/) service to optimize the files.
3. **Place the sprite**:
   - Add the generated sprite `icons.svg` to the `images` folder.

### Project Styling
1. **Create the `css` folder** if it does not exist.
2. Write all styles in one file called `styles.css`, located in the `css` folder.
3. **Include a style normalizer**:
   - [modern-normalize](https://cdnjs.com/libraries/modern-normalize).

### Links and Text Styling
1. **Set up GitHub Pages** for the repository.
2. Add a link to the live page in the `About` section of your GitHub repository.

---

## Acceptance Criteria for the Mentor

### Project
- **A1**: There is an `images` folder in the root of the project containing images.
- **A2**: All vector images are collected in the SVG sprite `icons.svg`, located in the `images` folder.
- **A3**: All vector images are optimized.
- **A4**: There is a `css` folder in the root of the project with style files.
- **A5**: All styles are written in one file `styles.css`.
- **A6**: The file names do not contain uppercase letters, spaces, or transliteration.
- **A7**: The code is formatted using Prettier.
- **A8**: All images and text content match the design mockup.
- **A9**: A style normalizer is included.
- **A10**: All styles are written in one file `styles.css`.
- **A11**: The code follows the provided guidelines.

### Markup
- **B1**: All icons are implemented using SVG.
- **B2**: The SVG icons are exported correctly (group selected, not individual vectors).
- **B3**: Icons from the SVG sprite are added to HTML using `<svg>` and `<use>` tags.
- **B4**: Icons are added in the advantages section (the section with the list of advantages over "Our Team").
- **B5**: Social media icons are added in the "Our Team" section.
- **B7**: Social media icons are added in the footer.
- **B8**: The HTML markup of all elements follows the design.
- **B9**: Semantic tags are used properly.

### Styling
- **C1**: The large image with a darkening effect (under the header) is set as a background with a gradient.
- **C2**: The background image does not stretch wider than its original size (1440px).
- **C3**: Cards in the "Our Team" section have a permanent shadow effect.
- **C4**: Cards in the "Our Portfolio" section have a shadow effect on hover.
- **C5**: Icons change color on hover or focus, as specified in the design.
- **C6**: Hover and focus effects (color, background, shadow) use transitions (250ms, `cubic-bezier(0.4, 0, 0.2, 1)`).
- **C7**: Transitions explicitly list the animated properties (no `all`).
- **C8**: In the main navigation, the current page link is underlined using the `::after` pseudo-element.
- **C9**: The overlay with text on cards in the "Our Portfolio" section appears on hover.
- **C10**: The blue overlay on the "Our Portfolio" cards slides up from the bottom.
- **C11**: Pseudo-elements do not contain text content in the `content` property and are used exclusively for decoration.

---

## Submission Format
1. **Link to the live page** (GitHub Pages).
2. **Link to the repository** with the source files.
3. **ZIP file of the repository**.

---

## Useful Services
- [Icomoon](https://icomoon.io/)
- [SVGOMG](https://jakearchibald.github.io/svgomg/)
- [Modern Normalize](https://cdnjs.com/libraries/modern-normalize)

--------------------------------------------------------

# Домашнє завдання: Тема 4. Декоративні ефекти. Анімація

## Інструкція щодо виконання завдання

### Підготовка
1. **Створіть новий репозиторій** з назвою `goit-markup-hw-04`.
2. **Склонуйте репозиторій** на локальний комп'ютер.
3. **Скопіюйте файли з попередньої роботи** в новий репозиторій.
4. Додайте розмітку і стилі згідно з вимогами завдання.

### Робота з SVG
1. **Генерація SVG-спрайту**:
   - Використайте сервіс [Icomoon](https://icomoon.io/) для створення SVG-спрайту.
2. **Оптимізація SVG-спрайту**:
   - Використайте сервіс [SVGOMG](https://jakearchibald.github.io/svgomg/) для оптимізації файлів.
3. **Розташування спрайту**:
   - Додайте згенерований спрайт `icons.svg` до папки `images`.

### Оформлення проєкту
1. **Створіть папку `css`**, якщо її ще немає.
2. Всі стилі напишіть в одному файлі `styles.css`, який розташовується в папці `css`.
3. **Підключіть нормалізатор стилів**:
   - [modern-normalize](https://cdnjs.com/libraries/modern-normalize).

### Оформлення посилань і тексту
1. **Налаштуйте GitHub Pages** для репозиторію.
2. Додайте посилання на живу сторінку в секцію `About` вашого GitHub-репозиторію.

---

## Критерії приймання роботи наставником

### Проєкт
- **A1**: У корені проєкту є папка `images` із зображеннями.
- **A2**: Всі векторні зображення зібрані в SVG-спрайт `icons.svg`, який знаходиться в папці `images`.
- **A3**: Всі векторні зображення оптимізовані.
- **A4**: У корені проєкту є папка `css` із файлами стилів.
- **A5**: Всі стилі написані в одному файлі `styles.css`.
- **A6**: У назвах файлів немає великих літер, пробілів та трансліту.
- **A7**: Вихідний код відформатований за допомогою Prettier.
- **A8**: Всі зображення і текстовий контент відповідають макету.
- **A9**: Підключений нормалізатор стилів.
- **A10**: Всі стилі написані в одному файлі `styles.css`.
- **A11**: Код написаний відповідно до настанови.

### Розмітка
- **B1**: Всі іконки реалізовані за допомогою SVG.
- **B2**: SVG-іконки експортовані коректно (обрана група).
- **B3**: Іконки з SVG-спрайту додаються через `<svg>` і `<use>`.
- **B4**: У секції переваг додані іконки.
- **B5**: У секції `Our Team` додані іконки соцмереж.
- **B7**: У футері додані іконки соцмереж.
- **B8**: Виконана HTML-розмітка всіх елементів макету.
- **B9**: Використані семантичні теги.

### Оформлення
- **C1**: Велике зображення з ефектом затемнення оформлене як фон із градієнтом.
- **C2**: Фонове зображення не розтягується ширше 1440px.
- **C3**: У картках секції `Our Team` є постійний ефект тіні.
- **C4**: У картках секції `Our Portfolio` ефект тіні з'являється при ховері.
- **C5**: При ховері/фокусі іконки змінюють колір.
- **C6**: Ефекти ховера/фокуса оформлені з переходами (250ms, `cubic-bezier(0.4, 0, 0.2, 1)`).
- **C7**: У переходах явно зазначені анімовані властивості.
- **C8**: У головній навігації підкреслення посилання реалізоване за допомогою псевдоелемента `::after`.
- **C9**: Оверлей з текстом на картках секції `Our Portfolio` з'являється при ховері.
- **C10**: Синій оверлей виїжджає знизу.
- **C11**: Псевдоелементи використовуються лише для декоративного оформлення.

---

## Формат здачі роботи
1. **Посилання на живу сторінку** (GitHub Pages).
2. **Посилання на репозиторій** із вихідними файлами.
3. **Файл репозиторію у форматі ZIP**.

---

## Корисні сервіси
- [Icomoon](https://icomoon.io/)
- [SVGOMG](https://jakearchibald.github.io/svgomg/)
- [Modern Normalize](https://cdnjs.com/libraries/modern-normalize)


### Формат оцінювання:
Залік / Незалік

**ВАЖЛИВО**  
Перегляньте Інструкцію щодо завантаження робочого файлу з репозиторію на GitHub.
