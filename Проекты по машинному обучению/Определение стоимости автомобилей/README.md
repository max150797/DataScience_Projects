Определение стоимости автомобилей
==========================================
Описание проекта
------------------------------------------
Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение, которое позволит привлечь новых клиентов, предоставляя им возможность узнать рыночную стоимость своего автомобиля. Для достижения этой цели мы строим модель, которая способна определять рыночную стоимость автомобилей на основе данных о их технических характеристиках, комплектации и ценах других автомобилей.

Критерии важные для заказчика:

1. Качество предсказания: Мы стремимся к высокому качеству предсказания, чтобы наши клиенты могли получить точную оценку рыночной стоимости своего автомобиля. Для этого мы используем современные алгоритмы машинного обучения, которые обеспечивают высокую точность предсказаний.

2. Время обучения модели: Мы понимаем, что заказчику важно, чтобы модель обучалась быстро, чтобы мы могли быстро внедрить изменения и улучшения. Поэтому мы используем эффективные методы обучения модели, которые позволяют нам значительно сократить время обучения.

3. Время предсказания модели: Мы придаем большое значение быстроте предсказания модели, чтобы наши клиенты могли мгновенно получить оценку стоимости своего автомобиля. Мы оптимизируем процессы предсказания и используем алгоритмы, чтобы обеспечить максимальную скорость работы модели.

Наша команда разработки поставила перед собой задачу создать эффективную модель, которая сочетает в себе высокое качество предсказания, быстрое время обучения и минимальное время предсказания. Мы уверены, что наше приложение сможет привлечь новых клиентов и удовлетворить потребности уже существующих, предоставляя им доступ к точной и актуальной информации о рыночной стоимости их автомобилей.

### Описание входных данных

**Признаки**
* DateCrawled — дата скачивания анкеты из базы
* VehicleType — тип автомобильного кузова
* RegistrationYear — год регистрации автомобиля
* Gearbox — тип коробки передач
* Power — мощность (л. с.)
* Model — модель автомобиля
* Kilometer — пробег (км)
* RegistrationMonth — месяц регистрации автомобиля
* FuelType — тип топлива
* Brand — марка автомобиля
* Repaired — была машина в ремонте или нет
* DateCreated — дата создания анкеты
* NumberOfPictures — количество фотографий автомобиля
* PostalCode — почтовый индекс владельца анкеты (пользователя)
* LastSeen — дата последней активности пользователя

**Целевой признак**
* Price — цена (евро)

![screenshot of sample](https://assets.avtocod.ru/storage/images/articles/stoimost-avto.jpg)
