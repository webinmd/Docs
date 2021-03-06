## Поля экспорта

| Поле | Название |
| -- | -- |
| id | Id Заказа | 
| num | Номер заказа |
| cart_cost | Стоимость покупок | 
| cost | Общая цена с доставкой |
| weight | Вес | 
| delivery | Доставка (id) |
| delivery_name | Доставка (название) | 
| delivery_cost | Цена доставки |
| payment | Оплата(id) | 
| payment_name | Оплата(название) |
| createdon | Дата создания заказа | 
| receiver | Получатель | 
| email | Почта |
| country | Страна |
| index | Почтовый индекс | 
| region | Область | 
| city | Город |
| metro | Станция метро |
| street | Улица |
| building | Здание |
| room | Комната |
| comment | Комментарий |
| user_id | Покупатель (id) |
| products_(имя поля) | Список купленных товаров. Например: **products_id** выведет список id товаров, **products_alias** - список алиасов товаров. |
| properties | Свойства |

>Для сохранения новых заказов нужно создать экспорт и активировать чекбокс 'Создание' в блоке 'Синхронизация'

## Свои поля в форме заказа

Если вы добавили свои поля по [инструкции](https://modx.pro/solutions/10040), то значение каждого поля будет выводиться в новой ячейке.
**Пример:**
Вы добавили 3 поля в форме заказа: **extfld_type**, **extfld_org**, **extfld_inn**
Поля для экспорта: **receiver**, **email**, **properties**

В таблицу будет сохранено 5 полей (каждое поле в новой ячейке): 
**receiver, email, extfld_type, extfld_org, extfld_inn**
