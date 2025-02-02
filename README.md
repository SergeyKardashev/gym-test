# Test task Gym with timer, popup and getting data from API

[Figma layout](https://www.figma.com/design/04GvwIiY1NqfAGq50ThaKs/%D0%A2%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D0%BE%D0%B5-Frontend?node-id=0-1&t=S5wf9XAklM82KfxY-1)

## Тестовое задание для кандидата на вакансию Frontend-разработчик
https://www.figma.com/file/9XgWK3p8hV7kGaeNbVqnpm/%D0%B4%D0%BB%D1%8F-%D0%B2%D0%B5%D1%80%D1%81%D1%82%D0%BA%D0%B8?type=design&node-id=0%3A1&mode=design&t=h09Rzn4ocBcWUV0t-1

* Сверстать все элементы первого экрана с тарифами.
* отобразить выделение тарифов при выборе, 
* на кнопку купить наложить анимационный эффект мигания (перехода у кнопки нет), 
* отобразить таймер на закрепленном хедере - поставить 2 минуты, 
* при остатке в 30 сек таймер мигает и выделяется красным, 
* установить чекбокс
* Разложить тарифы полученные от сервиса на страницу с тарифами, на первом экране
* Когда таймер заканчивается скидочные цены пропадают и остаются цены без скидки, предложить вариант как лучше это анимировать
* После этого появляется попап, где отображены ещё большие скидки, также полученные от сервиса
* При закрытии попапа остаемся на первом экране где отображаются тарифы без скидок
* Если хотите показать свои умения в адаптиве, то его можно сделать, но это не обязательный пункт
* Тестовое задание необходимо выполнить на следующий технологиях: React, Next, Taiwind.


## Получение данных от сервиса
### Ссылка на получение:  https://t-pay.iqfit.app/subscribe/list-test
### Пример одной записи:

```json
{
        "name": "1 неделя",
        "price": 699,
        "lengthInDays": 0,
        "isPopular": true,
        "isEndless": false,
        "isDiscount": false,
        "nonDiscountId": null,
        "id": "f347d050-073c-4969-ae91-7346f935cf70",
        "ownerId": "00000000-0000-0000-0000-000000000000",
        "statusId": null,
        "creationDateTime": "2024-03-07T14:18:38.5451758+03:00",
        "deleted": false
    },
```

### Необходимые для работы поля
* name - отображаемое имя тарифа
* price - цена тарифа
* isPopular - если true, то данный тариф необходимо отображать до истечения таймера
* isDiscount - если true. то данный тариф необходимо отображать на попапе

### Ты нам подходишь если: 
* Уверенно владеешь React, TypeScript, JavaScript и умеешь писать чистый и поддерживаемый код
* Ты хорошо и быстро верстаешь и умеешь делать адаптивные страницы.
* Ты умеешь разбираться в чужом коде
* У тебя был опыт разработки на Next.Js
* У тебя был опыт и ты понимаешь как работать с асинхронностью
* У тебя есть желание учиться и расти вместе с командой.

#### Будет плюсом, если ты знаешь:
* Redux
* Taiwind

### Мы используем в проектах:
* HTML
* CSS
* JavaScript
* TypeScript
* React
* Next
* Tailwind
* Redux (пока не используем, но в ближайшем будущем будем)
