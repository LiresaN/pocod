# ММвСС Лаболаторная работа №1
###### *У меня нет проектов на гитхабе, поэтому я решила сделать этот отчет*
## 1. Описание
В данной работе требуется построить имитационную модель СМО M/M/V с заданными характиристиками и параметрами СМО
### 1.1. Исходные данные и требования
  *Таблица 1 – Характеристики и параметры СМО*
     
| ПАРАМЕТР | ЕД.ИЗМЕРЕНИЯ | ЗНАЧЕНИЕ |
|----------------|:---------:|----------------:|
| Количество обсл. устройств| шт. | 10, 50, 100, 200, 500 |
| Удельная интенсивность нагрузки | Эрл | 0,14; 0,24; 0,34; 0,44; 0,54; 0,64; 0,74; 0,84; 0,94; 1 |
| Входящий поток | - | Простейший |
| Распределение времени обслуживания | - | Экспоненциальное |
| Среднее время обслуживания | Ед. времени | 1 |

   *Рисунок 1 – Структура модели СМО*
<p align="center">
  <img src="https://user-images.githubusercontent.com/83338875/116378464-d6207700-a81a-11eb-97e0-7b23a4731c52.png">
</p>

## 2. Построение имитационной модели СМО M/M/V
Имитационная модель включает в себя источник заявок (source), элемент выбора направления (SelectOutput), группу обслуживающих устройств, имитируемых элементами задержки (delay) и элемент завершения обслуженных заявок (sink) и элемент завершения неуспешных (потерянных) заявок (loss). Структура модели, построенной в AnyLogic, приведена на рисунке 2.
