WCounter — Android-проект
Название приложения: WCounter
Версия: 1.0
Автор: Oleksandr Nedbailo
Пакет: com.oleksandrnedbailo.wcounter

Проект использует встроенный Android WebView и локальную копию WCounter v65.
Данные сохраняются в DOM storage WebView.

Как собрать APK:
1. Откройте папку WCounter_Android в Android Studio.
2. Дождитесь синхронизации Gradle.
3. Выберите Build > Build Bundle(s) / APK(s) > Build APK(s).
4. APK появится в app/build/outputs/apk/debug/app-debug.apk.

Для публикации/распространения создайте собственную release-подпись через
Build > Generate Signed Bundle / APK. Не используйте debug APK как
постоянную публичную сборку.
