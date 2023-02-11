# Home manipulator


## $${\color{red}ПРОЕКТ \space\space В \space\space РАЗРАБОТКЕ}$$
## Ход разработки
- [X] Программная разработка
  - [X] Управление через инфракрасный пульт
    - [X] Написание первой версии программы для Arduino с управлением через ИК пульт
    - [ ] Разработка программы для настройки команд с любого из ИК пультов
  - [ ] Запись и воспроизведение команд
  - [X] Управление через ПК
    - [X] Написание программы для подачи сигналов с ПК на Arduino через USB
    - [X] Подключение к ПК USB камеры с подсветкой и крепление её к корпусу манипулятора
    - [X] Использование программ для удаленного доступа к рабочему столу для управления манипулятором через интернет с любого устройства
  - [ ] Отказ от ПК с целью обеспечения самодостаточности манипулятора и удобства управления
    - [ ] Написание программы для Arduino, позволяющей плате самостоятельно подключаться к интернету
    - [ ] Переход на использование Wi-Fi камеры
    - [ ] Создание сайта для управления манипулятором, подключение к первому трансляции с камеры

- [X] Разработка корпуса
  - [X] v0.0 Манипулятор на коллекторных двигателях
    - [X] Создание первых чертежей основания манипулятора
    - [X] Разработка чертежей плеч манипулятора под широко распространенные мотор редукторы типа TT Motor
    - [X] Разработка самодельных редукторов для расположения двигателей в плечах ближе к коленям и смещения центра тяжести
    - [X] Создание прототипа на коллекторных двигателях
    - [X] Отказ от коллекторных мотор-редукторов ввиду недостаточной мощности и невозможности адекватно контролировать скорость и угол вращения
  - [X] v1.0 Манипулятор на шаговых двигателях
    - [X] Разработка чертежей плеч манипулятора под имеющиеся шаговые двигатели
    - [X] Разработка конструкции клешни манипулятора
      - [X] Попытка использовать сервоприводный двигатель в конструкции клешни манипулятора, отказ ввиду слабого хвата получившейся клешни
      - [X] Попытка создания клешни наподобие ирисовой диаграммы, отказ ввиду чрезмерной громоздкости конструкции и слабого хвата
      - [X] 
    - [X] Создание прототипа на шаговых двигателях
  - [X] v1.1   
    - [X] В качестве эксперимента использование гидравлики в основании
    - [X] Отказ от гидравлики вследствие чрезмерного усложнения конструкции и ее утяжеления из-за жидкостей, принятие решения об использовании в дальнейшем шаговых двигателей 
  - [ ] v1.2
    - [ ] Создание кольцеобразного корпуса манипулятора
    - [ ] Переход на более доступные шаговые двигатели, разработка корпуса под них
    - [ ] Создание универсального прототипа


## Цели проекта
Домашний манипулятор - проект, целью которого является создание недорогого манипулятора для бытовых нужд. Манипулятор первой версии устанавливается в необходимых человеку местах для необходимых ему действий. Примеры использования:
+ Удаленное кормление различных видов домашних животных
+ Безопасное кормление экзотических и ядовитых животных (змей, пауков, ящериц)
+ Облегчение использование предметов быта для маломобильных групп населения
+ Удаленное наблюдение и контроль за детьми
+ В качестве "третьей руки" для различных точечных работ с мелкими предметами (захват, удержание, перенос)
+ Использование для "марких" работ
+ Для работы с аргессивными агентами, в т.ч. токсичными моющими средствами, едкими газами (клей, амиак-хлорсодержащими и др.)

## Диаграмма
Управление доступно через смартфон, пк и инфракрасный пульт (требуется предварительная настройка команд):


![image](https://user-images.githubusercontent.com/78417431/218278357-58b5cf29-08c1-464c-8c2e-af8f1392fe29.png)


## Внешний вид
С фотографиями проекта можно изнакомиться по [ссылке](https://drive.google.com/drive/folders/1YZTG0Izhqas_j91vWX19adGNBPf3R61k?usp=sharing)

