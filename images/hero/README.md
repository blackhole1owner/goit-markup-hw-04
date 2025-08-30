# Hero Background Image

Для правильної роботи hero секції потрібно додати фонове зображення.

## Вимоги до зображення:
- Формат: JPG або JPEG
- Назва файлу: `hero-bg.jpg`
- Рекомендовані розміри: 1440x800px або більше
- Розмір файлу: не більше 2MB

## Як додати зображення:
1. Помістіть файл `hero-bg.jpg` в цю папку
2. Зображення автоматично буде використано з темним оверлеєм
3. Фон буде розтягнуто на всю площу секції

## Поточні налаштування CSS:
```css
.hero-section {
    background-image: linear-gradient(rgba(46, 47, 66, 0.7), rgba(46, 47, 66, 0.7)), url(../images/hero/hero-bg.jpg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    max-width: 1440px;
    margin: 0 auto;
}
```
