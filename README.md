# task04_analysis
## Вкладка Network
Сохраненный профиль - lifehacker.ru.har

Некоторые CSS-файлы не минифицированы вообще.

Одни и те же html файлы несколько раз (скриншот html).

То же самое js (скриншот js).

Большинство js-ов загружаются до события DOMContentLoaded, вряд ли это необходимо (скриншот JS_before_DOMContentLoaded).

Ресурсы, которые долго ждут своей загрузки (ответ от сервера больше 200ms) - скриншоты slow_download1, slow_download2, slow_download3.

## Вкладка Performance
Сохраненный профиль - Profile-20190928T222045

First Paint - 1823.3ms  
First Meaningful Paint - 3206.7ms  
DOM Content Loaded - 5190.5ms  
Load - 17714.9ms  

Loading - 103ms  
Scripting - 972ms  
Rendering - 1236ms  
Painting - 101ms  

## Вкладка Coverage
Скриншот coverage.
Неиспользованный css - примерно 240 килобайт  
Неиспользованный js - примерно 2597 килобайт
