Собрать заготовку приложения для платформы Android (apk файл)

Из функционала, нужно реализовать вход в приложение по touch id (fingerprint).
Реализовать отдельную страницу (экран) где можно настроить вход в приложение по touch id.
Сама настройка заключается в указании юзером резервного pin-кода. После ввода pin-кода можно активировать вход по touch id.
Если настройка активирована, то при открытии приложения - должен запрашиватся touch id, и как резервный метод входа - вход по pin-коду. Никакого другого функционала в самом приложении реализовывать не нужно.


Используем следующие технологии:

https://cordova.apache.org/

https://framework7.io/vue/ - как раз и есть тот SPA фреймворк, который обеспечивает нативный внешний вид.

https://github.com/niklasmerz/cordova-plugin-fingerprint-aio - плагин touch id

Так же для сборки приложений под андроид нужно будет установить:

https://developer.android.com/studio - чисто для загрузки sdk (писать код в этой IDE не нужно)
https://www.oracle.com/java/technologies/javase/jdk11-archive-downloads.html - JDK для своей платформы (можно сразу не устанавливать, во время сборки, через cli оно подскажет)
