BOSS-HACK Android project

Это проект Android Studio, который открывает вашу HTML-версию BOSS-HACK V20
в полноэкранном WebView и устанавливается как отдельное приложение.

Как получить APK:
1. Распакуйте ZIP на компьютере.
2. Установите Android Studio.
3. Откройте папку BOSS_HACK_Android_Project через File -> Open.
4. Дождитесь Sync Project with Gradle Files.
5. Выберите Build -> Build Bundle(s) / APK(s) -> Build APK(s).
6. APK появится в app/build/outputs/apk/debug/app-debug.apk.

Для сборки нужен интернет при первой синхронизации Gradle и Android SDK Platform 35.
Приложение работает как оболочка для HTML. Оно не внедряется в Standoff 2 и не меняет
игровые файлы/сервер; доступность функций зависит от того, что реально реализовано в HTML.
