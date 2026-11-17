# PDF2FB2 — загрузки Android

## PDF2FB2 1.0.0 (debug, OCR offline)

- [Скачать APK — 47 MB](https://raw.githubusercontent.com/yury1978/PDF2FB2-downloads/v1.0.0-android-debug/PDF2FB2-1.0.0-debug.apk)
- [Скачать ZIP — 31 MB](https://raw.githubusercontent.com/yury1978/PDF2FB2-downloads/v1.0.0-android-debug/PDF2FB2-1.0.0-Android.zip)
- [SHA-256](https://raw.githubusercontent.com/yury1978/PDF2FB2-downloads/v1.0.0-android-debug/SHA256SUMS-1.0.0.txt)

Android 8.0/API 26 или новее. Пакет `pl.pdf2fb2`, versionCode 11.
Новая иконка, OCR польского/русского/английского и смешанного текста.
Все три модели внутри APK: интернет, Termux и Python не требуются.
Есть прогресс, отмена, редактирование текста и локальная проверка FB2 по XSD.
OCR может ошибаться: проверьте текст перед сохранением.

Это тестовый APK **debug**, не производственная подпись и не Google Play.
Сертификат тот же, что у опубликованного 0.9.1; обновление и конфликты подписей
проверены на изолированном эмуляторе. При другом сертификате экспортируйте
книги перед удалением предыдущей установки. Не удаляйте её без копий книг.

Подтверждено: 16/16 тестов на Android 8.0 x86_64, включая реальный OCR сканов,
работу без интернета, отмену, несколько страниц и экспорт FB2.
Восемь итоговых FB2 также проверены независимым lxml/XSD.
API35 не проверен: эмулятор прервал загрузку ОС (Watchdog), до установки приложения.
Физический телефон с этой версией пока не тестировался.

APK SHA-256: `a1da0636e5b3f6021d1cfe845907ca5bcc1424d3a9b92b47b89b645141f4ca55`.
Исходники приложения и ключи подписи здесь не публикуются.

## Архив предыдущего выпуска

## PDF2FB2 0.9.1 для Android

- [Скачать APK](https://raw.githubusercontent.com/yury1978/PDF2FB2-downloads/master/PDF2FB2-0.9.1.apk)
- [Скачать ZIP с APK и инструкцией](https://raw.githubusercontent.com/yury1978/PDF2FB2-downloads/master/PDF2FB2-0.9.1-Android.zip)
- [SHA-256](https://raw.githubusercontent.com/yury1978/PDF2FB2-downloads/master/SHA256SUMS.txt)

Техническая отладочная сборка. Требуется Android 8.0 (API 26) или новее.
Пакет `pl.pdf2fb2`, versionCode 10. Для установки из ZIP распакуйте архив и откройте APK.
Обновление предыдущей установки требует того же сертификата подписи.
OCR кириллицы на Android пока отсутствует. Исходники приложения и ключи подписи здесь не публикуются.
