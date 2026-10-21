DOT — Android game project
==========================

В проекте уже есть готовая игра: тёмный интерфейс, 30-секундный раунд,
счёт, случайное перемещение точки, экран результата и локальный рекорд.

Как собрать APK:
1. Установите Android Studio на компьютер.
2. Откройте папку DOT_Android через File > Open.
3. Дождитесь завершения Gradle Sync.
4. Выберите Build > Build Bundle(s) / APK(s) > Build APK(s).
5. APK появится в app/build/outputs/apk/debug/app-debug.apk.

Минимальная версия Android: 6.0 (API 23).
Сеть и разрешения не требуются. Рекорд хранится локально на устройстве.

Примечание: для сборки нужен Android SDK и подключение к интернету для загрузки
Gradle/Android Gradle Plugin при первом запуске Android Studio.
