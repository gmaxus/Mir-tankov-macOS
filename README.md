# Мир танков на macOS

Данная сборка позволяет играть в Мир танков без виртуальной Windows на macOS в 1 клик с Apple silicon и Intel процессором с работаюбщим Леста гейм центром и МОСТом (менеджер модов).

* [Установка модов](#установка-модов)
* [Как установить Общий тест](#общий-тест)
* [Шрифты (DXMT)](#DXMT)
* [Реплеи](#реплеи)
* [Настройки для Intel/AMD/Hackintosh](#настройки-для-intel)
* [Установка на внешний диск (Intel/AMD/Hackintosh)](#установка-на-внешний-диск)
* [Ошибки](#ошибки)

Видео с геймплеем:

#### [YouTube](https://www.youtube.com/watch?v=7CJCI_9IcEo)

#### [Rutube](https://rutube.ru/video/de6cbdcc3d2ae8d2a3a0896d3e77643e)



## Установка

Проект перешёл на донатно-подписочную основу. На Бусти размещены рабочие сборки. Также вы можете связаться со мной если Бусти вам не подходит по каким либо причинам.

http://t.me/tmaxus


Ниже версия для энтузиастов, в танки войти с её помощью НЕ получится, но клиент(сам мир танков) скачать можно:

**Apple silicon / Intel / AMD / Hackintosh**
``` text
http://git.thisismypage.ru/download/TeWQVSxBKyGXFPMfTQpzK4SPjLjMirnP3r7c70CVTjsSqtCLhLkdFwAVNedbWfv8
```

## Актуальные версии:
| Версия | Описание                                                                   |      Процессор      |    Дистрибуция     |
|:------:|----------------------------------------------------------------------------|:-------------------:|:------------------:|
|  4.1   | – Загрузка клиента Мира танков<br/> – Вход в Мир танков не возможен        | Apple silicon/Intel |       GitHub       |
| 4.4.1  | – Леcта Гейм Центр<br/> – МОСТ (менеджер модов)                            |    Apple silicon    |       Boosty       |
|  4.5   | – Леcта Гейм Центр<br/> – Шрифты без искажений                             |    Apple silicon    | Boosty (бета-тест) |
| 4.5.2  | – Леcта Гейм Центр<br/> – МОСТ (менеджер модов)<br/> – Шрифты без искажений |    Apple silicon    | Boosty (бета-тест) |

## Мой бусти

### [https://boosty.to/bmaxus](https://boosty.to/bmaxus)

<details>
  <summary><b>Почему проекту нужно спонсорство(кликабельно)</b></summary>


* Ежедневный мониторинг состояния проекта
  * Пройтись по площадкам(AppsTorrent, Телеграм, Youtube, ...) для решения проблем пользователей
* Поиск новых решений для улучшения сборки
  * Избавился от несрабатывания события зуммирования
  * Работает МОСТ
  * Автоматический перенос игры из старой в новую сборку
* Создание видео
  * Огромное количество дублей
  * Программы для записи экрана и звука
  * Монтирование
  * Размещение на видеоплощадках
* Осуществление техподдержки всех пользователей
  * на AppsTorrent
  * Телеграм
  * на Pikabu
  * Youtube
  * Rutube
* Адаптация сборки под обновления от Лесты
  * Почти с каждым обновлением Леста что-то меняет, приходится находить решения чтобы работало хорошо не только у меня, но и у всех пользователей на разных платформах
* Создание установочного файла
  * Подготовка текстов и изображений/скриншотов
  * Разработка и тестирование скриптов
  * Тестирование новых сборок и сбор обратной связи от бета-тестеров
* Создание самой сборки
    * Это 1 пункт, но он самый главный
* Организация и оплата хостинга для дистрибуции
  * Домен
  * VPS хостинг
  * Написание специализированного софта

#### Вся эта работа делается за вас для того чтобы вы могли дважды кликнуть на иконку и всё просто работало
</details>


# Внутренний магазин
Чтобы отображался магазин отключите **Аппаратное ускорение браузера**

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/shop-fix.jpg">

# Общий тест
Чтобы установить **Общий тест** когда он становится доступным, сделайте следующее:

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/pt/1.jpg">

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/pt/2.jpg">

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/pt/3.jpg">

# Ошибки
* [Красный треугольник](#ошибка-леста-гейм-центра)

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/lgc-error.jpg" width="400px"/>


* [Не удаётся установить соединение с сервером](#ошибка-соединения)

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/connection-error/connection-error.png">


# Установка модов
В **Программах** нажмите правой кнопкой мыши по **Мир танков** и выберете **Показать содержимое пакета**

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/7.jpg">

Откройте папку **Contents** и в ней **KegworksConfig**

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/8.jpg">

В открывшемся окне выберите **Install Software**

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/9.jpg">

Затем **Choose Setup Executable** и выберите установочный файл модов

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/10.jpg">

Будет сообщение об ошибке – нажмите **OK** и дождитесь начала установки модов

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/11.jpg">

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/12.jpg">

# Установка на внешний диск

1. Перенесите Мир танков и Обновить танки в **Applications**
2. Запустите файл **Команда**
3. Перенесите Мир танков и Обновить танки в **необходимое вам место**
4. Далее все действия производить в папке в которую перенесли 
5. Запустите **Обновить танки**
6. Дождитесь завершения загрузки Танков
7. Закройте **Обновить танки**
8. Запустите **Мир Танков**

Для обновления используйте **Обновить танки**


# Настройки для Intel

Нажать **Показать содержимое пакета**

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/intel/1.jpg">

Запустить **Kegworks Config.app**

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/intel/2.jpg">

Убрать **галочку**

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/intel/3.jpg">

На владке **Advanced** добавить галочку **MoltenVK FastMath** 

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/intel/4.jpg">


# Реплеи

Выполните команду в терминале:

``` text
ln -s "/Applications/Мир танков.app/Contents/SharedSupport/prefix/drive_c/Games" "/Applications/Tanki"
```

После чего в папке Программы появится папка Tanki

# DXMT

Можно вылечить шрифты и получить ~20% прирост в FPS, но будут другие проблемы:
1. При НЕ высокой графике проблемы с мышкой в бою – в право она очень плохо двигается, при том что в лево всё идеально
2. (иногда) При каждом нажатии левой или правой кнопки мыши отправляется сообщение в чат "двигаюсь в квадрат" или "двигаюсь в точку"
3. Нельзя менять пропорции разрешения дисплея, всегда будет максимальное(21:13 для ноутбуков М-серии), из-за чего чёлка будет закрывать часть дисплея
4. Не сильно существенные баги в ангаре

В некоторых случаях это рабочий вариант

Нажать **Показать содержимое пакета**

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/dxmt/1.jpg">

Запустить **Kegworks Config.app**

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/dxmt/2.jpg">

Выбрать **галочку**

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/dxmt/3.jpg">


# Ошибка соединения

Если вы видите такое сообщение при попытке подключиться к серверу:

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/connection-error/connection-error.png">

Включите общий доступ

Сделайте следующее:

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/connection-error/0.jpg">

Переключатель должен быть активен

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/connection-error/1.jpg">


Если включение общего доступа не помогло, введите это в терминале:

``` text
sudo sed -i.bak "s/^127.0.0.1.*/127.0.0.1 localhost $(hostname)/" /etc/hosts
```

Или если вы знаете что делаете, поправьте команду соответственно с вашим hosts

Эта команда изменяет строку:

``` text
127.0.0.1	localhost
```
на:

``` text
127.0.0.1	localhost	Maksims-MacBook-Pro.local
```

где:
* 127.0.0.1 – ваш дефолтный локальный айпи
* localhost – дефолтный локальный хостнэйм
* Maksims-MacBook-Pro.local – локальный хостнэйм

# Ошибка Леста гейм центра
<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/lgc-error.jpg"/>

1. У вас недостаточно свободного места на диске
2. Если места достаточно – перезагрузитесь и запустите установку заново