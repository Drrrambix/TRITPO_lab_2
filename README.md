# TRITPO_lab_2
# ТРЕБОВАНИЯ К ПРОЕКТУ

### Содержание:
1. [Введение](#1) <br>
 1.1. [Назначение](#1.1) <br>
 1.2. [Бизнес-требования](#1.2) <br>
   1.2.1. [Исходные данные](#1.2.1) <br>
   1.2.2. [Возможности бизнеса](#1.2.2) <br>
   1.2.3. [Границы проекта](#1.2.3) <br>
 1.3 [Аналоги](#1.3) <br>
2. [Требования пользователя](#2) <br>
2.1. [Программные интерфейсы](#2.1) <br>
2.2. [Интерфейс пользователя](#2.2) <br>
2.3. [Характеристики пользователей](#2.3) <br>
2.3.1.[Классификация пользователей](#2.3.1) <br>
2.3.2[Целевая аудитория](#2.3.2) <br>
2.4. [Предположения и зависимости](#2.4) <br>
3. [Системные требования](#3) <br>
3.1. [Функциональные требования](#3.1) <br>
3.1.1. [Выбор способа проведения досуга](#3.1.1) <br>
3.1.2 [Оценка фильма](#3.1.2) <br>
3.1.3. [Выбор предостовляемых курсов](#3.1.3) <br>
3.1.4. [Уровень сложности курса](#3.1.4) <br>
3.2. [Нефункциональные требования](#3.2) <br>
3.2.1. [Визуальный стиль](#3.2.1) <br>
3.2.2. [Требования к удобству](#3.2.2) <br>
3.2.3.[Ограничения](#3.2.3)<br>

### 1. Введение <a name="1"></a>
#### 1.1 Назначение <a name="1.1"></a>
Этот документ является основным источником с требованиями к боту «KinoProga-бот» для Telegram.

#### 1.2 Бизнес-требования <a name="1.2"></a>
##### 1.2.1 Исходные данные <a name="1.2.1"></a>
Наше время, век глобальной компьютеризации и информатизации, предоставляет современному человеку невиданные ранее средства усиления его умственных возможностей, средства, позволяющие к тому же сделать интенсивными процессы интеллектуального развития. Так, использование возможностей средств современных информационных технологий позволяет приобретать знания, релаксировать и создавать нечто уникальное, не выходя из зоны комфорта, в чем помогает техника и программное обеспечение. Создание телеграмм-бота KinoProga выступает идейным генератором для просмотра фильмов и изучения программирования с помощью бесплатных специальных курсов. Уникальная возможность после прекрасного отдыха провести время с пользой, проработав свои навыки. 

##### 1.2.2. Возможности бизнеса <a name="1.2.2"></a>
Многие люди желают иметь сервис, который предоставляет возможность проведения досуга с пользой в удобной и легкодоступной форме. Именно представленный проект по созданию телеграмм-бота поможет решить сразу две проблемы: выбор фильма и изучения специальных курсов программирования совершенно бесплатно. 

##### 1.2.3. Границы проекта <a name="1.2.3"></a>
Приложение «KinoProga-бот» позволит пользователям совмещать приятное с полезным: просматривать увлекательные фильмы и практиковаться в программировании.

#### 1.3 Аналоги <a name="1.3"></a>
??

### 2. Требования пользователя <a name="2"></a>
#### 2.1. Программные интерфейсы <a name="2.1"></a>
Приложение должно работать в Telegram клиенте версии не ниже 6.0.0. В приложении должен использоваться Telegram Bot API версии 6.2. Должно быть написано на языка Python 3.10 и данных храниться в базе данных SQLite версии 3.39.4.

#### 2.2. Интерфейс пользователя <a name="2.2"></a>
При запуске должен отражаться диалог приветствия.
После диалога приветствия должен отражаться диалог первичной настройки.

![диалог](исходники/Start.jpg)

Так должен выглядеть диалог при желании посмотреть фильм.

А так выглядит диалог для выбора изучаемого курса программирования.


#### 2.3. Характеристики пользователей <a name="2.3"></a>
### 2.3.1 Классификация пользователей <a name="2.3.1"></a>
Пользователи,которые установили данное приложение будут иметь доступ к полному функционалу программы.
### 2.3.2 Целевая аудитория <a name="2.3.2"></a>
Приложение предназначено для всех групп пользователей, которым интересен просмотр фильмов и/или изучения программирования.

#### 2.4. Предположения и зависимости <a name="2.4"></a>
1. Приложение не работает при отсутствии подключения к Интернету.
2. Приложение не работает при отсутствии Telegram.

### 3. Системные требования <a name="3"></a>
 Процессор с тактовой частотой 800 MHz или более мощный.Оперативная память 128 MB. Свободное место на жёстком диске от 49 Мб.

#### 3.1. Функциональные требования <a name="3.1"></a>
Пользователю предоставлены возможности, представленные ниже.

##### 3.1.1. Выбор способа проведения досуга.<a name="3.1.1"></a>
Приложение должно предоставить выбор между предостовляемыми услугами.
##### 3.1.2. Оценка фильма.<a name="3.1.2"></a>
Приложение должно предоставить возможность оценки просмотренного фильма.
##### 3.1.3. Выбор предостовляемых курсов.<a name="3.1.3"></a>
Приложение должно предоставить список тем курсов для обучения.
##### 3.1.4. Уровень сложности курса.<a name="3.1.4"></a>
Приложение должно предоставить выбор уровня сложности курса в зависимости от опыта пользователя.

#### 3.2. Нефункциональные требования <a name="3.2"></a>
##### 3.2.1. Визуальный стиль <a name="3.2.1"></a>
Визуальный стиль приложения должен быть выполнен в нейтральных цветах в меню выбора марки автомобиля,и менять свой цвет под фирменный цвет марки при переходе в дальнейшие меню.
##### 3.2.2. Требования к удобству <a name="3.2.2"></a>
Должна быть легкость использования засчет минималистичного интерфейса, удобство в использовании пользователями любого уровня технической грамотности. Должна быть обратная связь с пользователем.

 ##### 3.2.3. Ограничения <a name="3.2.3"></a>
1. Приложение работает только при наличии подключения к Интернету.
2. Приложение не работает при отсутствии Telegram.
3.Язык приложения русский.
