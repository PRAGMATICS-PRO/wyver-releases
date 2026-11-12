# Wyver — сборки для Windows

Здесь только готовые сборки Wyver — VPN-клиента для Windows 10 и 11 (64-бит).

## Как установить

1. Откройте [последний релиз](../../releases/latest) и скачайте `wyver-X.Y.Z.zip`.
2. Распакуйте в отдельную папку, например `C:\Wyver`, и запустите `wyver.exe`. Wyver попросит права администратора — они нужны, чтобы создать сетевой адаптер VPN.
3. Если Windows покажет «Windows защитила ваш компьютер», нажмите «Подробнее» → «Выполнить в любом случае». Сборки пока не подписаны сертификатом разработчика.

## Обновления

С версии 0.2.0 Wyver сам проверяет новые версии — при запуске и в «Настройки → О программе». Обновление ставится только по вашей кнопке. Каждая версия подписана ключом выпуска, и Wyver не поставит сборку без верной подписи.

Файлы `latest.json` и `latest.json.sig` в релизах — для этой проверки.

---

# Wyver — Windows builds

Ready-made builds of Wyver, a VPN client for Windows 10 and 11 (64-bit).

**Install:** download `wyver-X.Y.Z.zip` from the [latest release](../../releases/latest), unpack it into its own folder (e.g. `C:\Wyver`) and run `wyver.exe` (it asks for administrator rights to create the VPN adapter). If Windows says "Windows protected your PC", click "More info" → "Run anyway": the builds are not code-signed yet.

**Updates:** since 0.2.0 Wyver checks for new versions at launch and in Settings → About, and installs only when you press the button. Every release is signed; Wyver refuses a build without a valid signature.
