# Dispatcher Info (Addon for Metrostroi)

**Created by:** Alexell

**Website:** https://alexell.ru/

![Dispatcher Info](https://mss.community/images/addons/disp-info.jpg)

**Описание:**

Серверный аддон, который добавляет в правой части экрана небольшую панель для отображения диспетчера на посту, а также интервала движения.

**Возможности:**
* Интеграция с ULX (назначаете доступ к командам по группам)
* !disp - занять пост ДЦХ
* !undisp - освободить пост ДЦХ
* !setdisp - назначить на пост ДЦХ (команда для админов)
* !int - установить интервал движения
* интервал движения по умолчанию: 2.00

**Список хуков:**
* **DispInfoTookPost** (ник игрока) - выполняется, когда игрок заступил на пост
* **DispInfoFreedPost** (ник игрока) - выполняется, когда игрок покинул пост
* **DispInfoSetInt** (ник игрока, интервал) - выполняется, когда диспетчер изменил интервал

**Необходимые аддоны:**

* Metrostroi
* ULX
* ULib

**Установка:**

* Добавить в коллекцию сервера: https://steamcommunity.com/sharedfiles/filedetails/?id=1673775394

или

* распаковать [архив с нужной версией](https://github.com/Alexell/disp-info/releases) в **garrysmod\addons** на вашем сервере
