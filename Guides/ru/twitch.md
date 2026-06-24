# Twitch: двухфакторная аутентификация

Twitch включает 2FA через настройки безопасности. Исторически Twitch завязан на телефон и Authy/Twilio-поток, поэтому добавляйте его в это приложение только если Twitch прямо показывает QR-код или ключ для authenticator app.

1. Откройте Twitch.
2. Перейдите в **Settings**.
3. Откройте **Security and Privacy**.
4. Найдите **Two-Factor Authentication**.
5. Нажмите **Set Up Two-Factor Authentication**.
6. Подтвердите телефон, если Twitch попросит.
7. Если появится QR-код или setup key для authenticator app, отсканируйте его этим приложением.
8. Если Twitch предлагает только SMS/Authy без QR-кода или ключа, такой способ не добавляется как TOTP-код.
9. Сохраните recovery codes.

Официальная справка: [Two-Factor Authentication](https://help.twitch.tv/s/article/two-factor-authentication).
