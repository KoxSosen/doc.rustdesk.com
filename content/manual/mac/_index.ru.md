---
title: Mac 
weight: 3
---

### Установка
------

Откройте файл .dmg и перетащите `RustDesk` в `Applications` как на картинке ниже.

![](/docs/en/manual/mac/images/dmg.png)

Убедитесь, что вы закрыли все запущенные приложения RustDesk. Также убедитесь, что вы закрыли службу RustDesk.

![](/docs/en/manual/mac/images/tray.png)

### Разрешение на запуск RustDesk

| Разблокируйте для изменения | Нажмите на "App Store and identified developers" |
| ---- | ---- |
|![](/docs/en/manual/mac/images/allow2.png)|![](/docs/en/manual/mac/images/allow.png)|

### Включение разрешений

{{% notice note %}}
Due to MacOS security policy change, our api which captures input on local side does not work any
more. You have to enable "Input Monitoring" permission on local Mac side.
Please follow this
[https://github.com/rustdesk/rustdesk/issues/974#issuecomment-1185644923](https://github.com/rustdesk/rustdesk/issues/974#issuecomment-1185644923)

It seems no quick fix, we need to fix together with our Flutter version.
{{% /notice %}}

Чтобы захватывать экран требуются разрешения **accessibility** и **screen recording**. RustDesk поможет их настроить.

| Окно RustDesk | Окно настроек |
| ---- | ---- |
|![](/docs/en/manual/mac/images/acc.png)|![](/docs/en/manual/mac/images/acc3.png?v2)|

Если разрешения включены, но RustDesk их не видит, то уберите RustDesk из списка при помощи кнопки `-`, затем нажмите кнопку `+` и выберите RustDesk в `/Applications`.

| Кнопки `-` и `+` | Выбор RustDesk |
| ---- | ---- |
|![](/docs/en/manual/mac/images/acc2.png)|![](/docs/en/manual/mac/images/add.png?v2)|

Пройдите те же шаги для настройки разрешения **screen recording**.

![](/docs/en/manual/mac/images/screen.png?v2)
