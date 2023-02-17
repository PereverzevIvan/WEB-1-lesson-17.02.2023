# Изучение методологии БЭМ
## Задание №1 - Человеческое тело
---
### .голова
+ .голова__глаз
    - .голова__глаз--цвет_зеленый
+ .голова__ухо
    - .голова__ухо--размер_большой
+ .голова__нос
    - .голова__нос--состояние_забитый

### .нога
+ .нога__бедро
+ .нога__голень
+ .нога__ступня

### .рука
+ .рука__предплечье
+ .рука__запястье
+ .рука__палец
---
## Задание №2 - БЭМ по макету (5 вариант)
---
### Header
![header](/header.png)
```
header.header>div.header__container>(a.header__logo>img)+(nav.header__nav>a.header__link*5)+button.btn
```

### Форма
![form](/form.png)
```
form.form>(label.form__label.form__label_hidden+input.form__input)*2+(div.separator>label.form__label.form__label_small.form__label_hidden+input.form__input.form__input_small)*2+label.form__label.form__label_hidden+textarea.form__input.form__textarea+button.btn.btn_black
```