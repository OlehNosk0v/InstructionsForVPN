# InstructionsForVPN

Эта инструкция как установить клиент VPN на ваше устройство. Здесь будут две программы:

* [Установка](#Установка)
    * [На Windows и Linux](#WindowsAndLinux)
      * [V2rayN](#V2rayN)
      * [AmneziaVPN (Не рекомендуется)](#AmneziaVPN-PC)
    * [На Android](#Android)
      * [V2rayNG](#V2rayNG)
        * [(Опционально) Установка программы для автообновления и упрощения установки](#Опционально-Установка-программы-для-автообновления-и-упрощения-установки)
      * [AmneziaVPN (Не рекомендуется)](#AmneziaVPN-Mobile)
* [Настройки маршутизации](#Настройки-маршутизации)

# Установка

## WindowsAndLinux 

### V2rayN

Скачайте [V2rayN](https://github.com/2dust/v2rayN) на ПК

| ![Win1](https://github.com/OlehNosk0v/InstructionsForVPN/blob/main/material/Win1.png)   | ![Win2](https://github.com/OlehNosk0v/InstructionsForVPN/blob/main/material/Win2.png)   |
| --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| Справа найдите вкладку "Release" и нажмите на последнюю версию                          | Выберите программу под вашу ОС                                                          |

Распокуйте и запустите программу.
<br>

![Win3](https://github.com/OlehNosk0v/InstructionsForVPN/blob/main/material/Win3.png)

Чтобы добавить ключ, просто скопируйте его и вставьте в программу через клавишу *Ctrl+V* или "Серверы" -> "Импорт массива URL из буфера обмена".

Чтобы добавить [правила маршутизации](#Настройки-маршутизации), нажмите сверху на "Настройки" -> "Настройки маршутизации" -> "Добавить" -> "Импорт правил из буфера обмена".
Теперь в примичании назовате так, как вам удобно. В списке правил маршутизации найдите созданный вами и правой кнопкой мыши кликните на него и установите как активное правило.

Готово!

Чтобы включить VPN, слево снизу нажмите на ползунок "Режим VPN", также аналогично и для выключения.

  
### AmneziaVPN PC

**Почему не рекомендуется**
*AmneziaVPN не имеет обширного функционала и технологий VLESS. В данный момент это не критично и им можно пользоваться, однако в будущем при обновление ключей и технологий AmneziaVPN может стать несовместимым. Также у него отстуствует адекватная маршутизация, из-за чего весь трафик идёт через VPN, а не раздельно как у других*

Скачайте [AmneziaVPN](https://github.com/amnezia-vpn/amnezia-client) на ПК

| ![Win1](https://github.com/OlehNosk0v/InstructionsForVPN/blob/main/material/Win1.png)   | ![Win4](https://github.com/OlehNosk0v/InstructionsForVPN/blob/main/material/Win4.png)   |
| --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| Справа найдите вкладку "Release" и нажмите на последнюю версию                          | Выберите программу под вашу ОС                                                          |

Дальше

## Android

### V2rayNG

Если вы желаете сами установить и настроить своими ручками, то вот программа: 
https://github.com/2dust/v2rayNG

| ![v2rayNG1](https://github.com/OlehNosk0v/InstructionsForVPN/blob/main/material/V2rayNG1.png) | ![v2rayNG2](https://github.com/OlehNosk0v/InstructionsForVPN/blob/main/material/V2rayNG2.png) |
| --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| Найите вкладку "Release" справа или внизу и нажмте на последнюю версию                        | Скачайте программу, где имеется название "arm64" или "universal"                              |

#### (Опционально) Установка программы для автообновления и упрощения установки
Скачайте [Obtainium](https://github.com/ImranR98/Obtainium) - это менеджер программ для автообновления и удобства скачивания из разных источников.
[Лист APK файлов](https://github.com/ImranR98/Obtainium/releases) - выбирайте `app-arm64-v8a-release.apk` и устанавливайте на устройство.
<br>
![4](https://github.com/OlehNosk0v/InstructionsForVPN/blob/main/material/4.png)
<br>

Дальше уже заходим в саму программу:

| ![1](https://github.com/OlehNosk0v/InstructionsForVPN/blob/main/material/1.jpg)   | ![2](https://github.com/OlehNosk0v/InstructionsForVPN/blob/main/material/2.jpg)                                                               | ![3](https://github.com/OlehNosk0v/InstructionsForVPN/blob/main/material/3.jpg)   |
| --------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| 1. При установке Obtainium нажмите снизу на кнопку "Добавить"                     | 2. Скопируйте ссылку:<br>https://github.com/2dust/v2rayNG<br>и вставьте в поле URL-адреса.<br>3. Нажмите на "добавить" и подождите пару минут | 4. Когда покажется экран программы, нажмите снизу на "Установить"                 |

Поздравляю, вы скачали программу. Теперь время настраивать его.

#### Настройка VPN:

| ![5](https://github.com/OlehNosk0v/InstructionsForVPN/blob/main/material/5.jpg)  | ![6](https://github.com/OlehNosk0v/InstructionsForVPN/blob/main/material/6.jpg)   |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Зайдя в программу, нажмите на "+" сверху справа, чтобы добавить профиль VPN      | Скопируйте ключ, который был вам отправлен, и нажмите на "Импорт из буфер обмена" |

Вы можете теперь пользоваться VPN, однако также следует настроить маршутизацию, чтобы повысить шансы подозрение провайдера на использование VPN:

| ![7](https://github.com/OlehNosk0v/InstructionsForVPN/blob/main/material/7.jpg)  | ![8](https://github.com/OlehNosk0v/InstructionsForVPN/blob/main/material/8.jpg)   | ![9](https://github.com/OlehNosk0v/InstructionsForVPN/blob/main/material/9.jpg)   | ![10](https://github.com/OlehNosk0v/InstructionsForVPN/blob/main/material/10.jpg)                  |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| Нажмите слево сверху на меню                                                    | Выберите вкладку "Маршутизация"                                                    | Нажмите на "+" сверху справа                                                      | Скопируйте [настройки мрашутизации](#Настройки-маршутизации) и нажмите на "Импорт правил из буфера обмена" |


# Настройки маршутизации

```json
[
  {
    "outboundTag": "direct",
    "domain": [
      "userapi.com",
      "*.userapi.com"
    ],
    "enabled": true
  },
  {
    "outboundTag": "direct",
    "domain": [
      "vk.com",
      "*.vk.com"
    ],
    "enabled": true,
    "remarks": "VK"
  },
  {
    "outboundTag": "direct",
    "domain": [
      "regexp:.*\\.ru$"
    ],
    "enabled": true
  },
  {
    "outboundTag": "direct",
    "ip": [
      "geoip:ru"
    ],
    "enabled": true
  },
  {
    "outboundTag": "block",
    "domain": [
      "geosite:category-ads-all"
    ],
    "enabled": true,
    "remarks": "\u0411\u043B\u043E\u043A\u0438\u0440\u043E\u0432\u043A\u0430 \u0440\u0435\u043A\u043B\u0430\u043C\u044B"
  },
  {
    "outboundTag": "direct",
    "ip": [
      "geoip:private"
    ],
    "enabled": true,
    "remarks": "\u041F\u0440\u0438\u0432\u0430\u0442\u043D\u044B\u0435 \u0441\u0435\u0442\u0438 \u043D\u0430\u043F\u0440\u044F\u043C\u0443\u044E"
  },
  {
    "outboundTag": "direct",
    "domain": [
      "geosite:private"
    ],
    "enabled": true,
    "remarks": "\u041F\u0440\u0438\u0432\u0430\u0442\u043D\u044B\u0435 \u0434\u043E\u043C\u0435\u043D\u044B \u043D\u0430\u043F\u0440\u044F\u043C\u0443\u044E"
  },
  {
    "port": "0-65535",
    "outboundTag": "proxy",
    "enabled": true,
    "remarks": "\u041E\u0441\u0442\u0430\u043B\u044C\u043D\u043E\u0435 \u0432 \u043F\u0440\u043E\u043A\u0441\u0438"
  }
]
```
