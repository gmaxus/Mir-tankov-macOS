# Как играть в Мир танков на macOS
Мир танков отлично работает на macOS без Windows на эмуляторах основанных на [Wine](https://winehq.org/) таких  как [Crossover](https://www.codeweavers.com/crossover) или [Whiskey](https://getwhisky.app/). Но к сожалению [Lesta Game Center](https://redirect.lesta.ru/LGC/Lesta_Game_Center_Install_RU.exe)(LGC) который скачивает и обновляет Мир танков не может нормально работать на эмуляторах

Данная сборка:

* Без виртуальной Windows
* Может скачивать и устанавливать обновления Мира танков
* Нет глюков с вращающимеся гусеницами
* Магазин отображается без искажений
* Нет проблем с изменёнными цветами
* По умолчанию скачивается HD клиент
* Занимает около 85 Гб
* Предназначена для Стандартной графики

### На бусти появилась сборка с работающим Lesta Game Center
#### [https://boosty.to/bmaxus](https://boosty.to/bmaxus)

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/macOS-LGC.jpg">

## Установка
``` text
http://xerocop.ru/git/tanki-V3.zip
```
* Скачайте
* Разархивируйте
* Переместите **LGC** и **Tanki** в папку **Программы**

Выполните следующую команду в **Терминале**
```text
xattr -r -c /Applications/Tanki.app
```

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/22.jpg">

Запустите **LGC** – начнётся скачивание

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/0.jpg">

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/1.jpg">

По окончании скачивания вы увидите следующее

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/2.jpg">

Закройте **Lesta Game Center**

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/3.jpg">

Запустите **Tanki**

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/4.jpg">

Вы великолепны!

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/5.jpg">

# Обновления

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/6.jpg">

Если вы видите что Мир танков стал сообщать о необходимости обновления игры, то запустите **LGC** (Мир танков при этом должен быть закрыт) он скачает и установит все обновления сам

После того как обновления будут установлены, закройте **Lesta Game Center** и только после этого запускайте **Мир танков** 



# Доработки
Чтобы отображался магазин отключите **Аппаратное ускорение браузера**

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/shop-fix.jpg">

Если возникнут подлагивания звука, то это лечится включением опции **Низкое качество** в настройках звука. У меня такой проблемы нет, но есть на Crossover

<img src="https://raw.github.com/gmaxus/Mir-tankov-macOS/main/img/sound-fix.jpg">

# Установка модов
В **Программах** нажмите правой кнопкой мыши по **Tanki** и выберете **Показать содержимое пакета**

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