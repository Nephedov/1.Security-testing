# «Введение в тестирование безопасности»

## Решения
#### Задание 1
* <a href="https://drive.google.com/file/d/1V4euEXu7AWu6ivVopTUS4_0s0UgEAFVe/view">Скриншот</a> - UDP пакета.

  
#### Задание 2
* <a href="https://drive.google.com/file/d/1HLa30-KHfvMnH_48kwUifrn7IN3aRGhH/view">Скриншот</a> - DNS пакета.

  
## Что было сделано
* Установлены локально:
  * [Wireshark](https://www.wireshark.org/download.html).
  * [Firefox](https://www.mozilla.org/ru/firefox/new/).
#### Задание 1
* Отловлен пакет с протоколом UDP, трафика интерфейса выхода в интернет, используя [Wireshark](https://www.wireshark.org/download.html).
* Определены порты передачи данных - <a href="https://drive.google.com/file/d/1V4euEXu7AWu6ivVopTUS4_0s0UgEAFVe/view">Скриншот</a>.


#### Задание 2
* Отловлен пакет с протоколом DNS, трафика интерфейса выхода в интернет, используя [Wireshark](https://www.wireshark.org/download.html).
* Определены обнаруженные флаги - <a href="https://drive.google.com/file/d/1HLa30-KHfvMnH_48kwUifrn7IN3aRGhH/view">Скриншот</a>.

---
---


## Описание Задания 1. Wireshark, UDP

1. Запустите захват трафика с интерфейса, через который выходите в интернет.
2. В фоне запустите браузер и перейдите на любой сайт.
3. Отфильтруйте в трафике протокол UDP.
4. Выберите любой пакет.
5. Откройте уровень UDP.
6. Определите, между какими портами происходит передача данных. Нас интересуют поля sourсe port, destanation port.


## Описание Задания 2. Wireshark, DNS

1. Отфильтруйте в трафике протокол DNS.
2. Выберите любой пакет.
3. Откройте уровень DNS.
4. Напишите, какие флаги протокола DNS вам удалось обнаружить.
