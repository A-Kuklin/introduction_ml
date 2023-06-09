# Рекомендация тарифов
  * [Описание исследования](#Описание-исследования)
  * [Описание данных](#Описание-данных)
  * [Общий вывод](#Общий-вывод)
## Описание исследования
В вашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы (из проекта курса «Статистический анализ данных»). Нужно построить модель для задачи классификации, которая выберет подходящий тариф. Предобработка данных не понадобится — вы её уже сделали.

Постройте модель с максимально большим значением *accuracy*.<br>
Чтобы сдать проект успешно, нужно довести долю правильных ответов по крайней мере до 0.75.<br>
Проверьте *accuracy* на тестовой выборке самостоятельно.
## Описание данных
* `сalls` — количество звонков,
* `minutes` — суммарная длительность звонков в минутах,
* `messages` — количество sms-сообщений,
* `mb_used` — израсходованный интернет-трафик в Мб,
* `is_ultra` — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).
## Общий вывод
Доля правильных ответов модели, которая игнорирует входные параметры,
меньше доли правильных ответов выбранной модели.<br>
Выбранная модель прошла проверку на адекватность.
***
_Работа над проектом велась в PyCharm 2021.3.2 (Professional Edition)_<br>
_формат ячеек Markdown различается в веб-версии и в PyCharm_