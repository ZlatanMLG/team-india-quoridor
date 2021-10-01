# Quoridor

## Team India

### Учасники:
- Степанюк Роман ([@rmnstepaniuk](https://t.me/rmnstepaniuk))
- Желепа Валентин ([@zlatanmlg](https://t.me/zlatanmlg))
- Кучеренко Іван (@\_iku4er\_)

## Завдання

Quoridor - настільна гра для двох або чотирьох гравців з достатньо простими правилами, але глибокою стратегією.

В рамках завдання неохідно створити програму, що виконує наступні вимоги:
- програма є клієнтом для гри у Quoridor для двох гравців;
- користувач може обрати: або ходити за обох опонентів, або грати проти комп'ютерного гравця який грає за примітивною стратегію - робить випадковий із можливих кроків. (Тобто або рухається у випадковому напрямку, або виставляє стінку у випадкове дозволене місце);
- програма не дозволяє робити не коректні ходи;
- програма фіксує переможця;

На програмному рівні має бути виділено три компонента:
- відображення - ui-код, що відноситься до рендеру клієнта. Вимог до реалізації немає, це може бути як стенделоун-додаток, так і команда строка з ASCII-артом або веб-сторінка.
- введення - частина програми, що оброблює інпут та перенаправляє його в модель. Дуже важливо чітко виділити цей компонент, оскільки в другій роботі його доведеться замінити на ввід з командної строки.
- модель - весь код, що відноситься до бізнес-логіки, тобто гри Quoridor. Ця частина коду знадобиться в наступній роботі, де не буде необхідності в виводі результату на екран, і буде інший інпут
