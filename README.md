# Установка Archi

1. Установить Archi

https://www.archimatetool.com/download/

2. Установить CoArchi plugin. Устанавливается через меню Help - Manage Plug-ins.

https://www.archimatetool.com/plugins/

3. Зайти в настройки Edit - Preferences - Collaboration и заполнить Name и Email.

4. Зарегистрироваться на github.com

5. Сгенерировать усиленный пароль по ссылке https://github.com/settings/tokens

6. Направить на почту mirambek.mustafin@zerde.gov.kz свой логин на github.com
7. Добавить в файл .gitconfig (находится в C:\Users\{наименование учетной записи}) следующий код:

```
[filter "lfs"]
    process = git-lfs filter-process
    required = true
    clean = git-lfs clean -- %f
    smudge = git-lfs smudge -- %f
[https]
    sslVerify = false
[http]
    sslVerify = false
```
    
# Адреса архитектурных моделей

### Трансформация Зерде
https://github.com/ICTHoldingZERDE/transformation

### Трансформация НИТ
https://github.com/ICTHoldingZERDE/nit-transformation

### ИТС МИИР
https://github.com/ICTHoldingZERDE/its

### Архитектура государства
https://github.com/ICTHoldingZERDE/govarch

# Адреса архитектурных моделей для новых пользователей (приглашения)

### Трансформация Зерде
https://github.com/ICTHoldingZERDE/transformation/invitations

### Трансформация НИТ
https://github.com/ICTHoldingZERDE/nit-transformation/invitations

### ИТС МИИР
https://github.com/ICTHoldingZERDE/its/invitations​

### Архитектура государства
https://github.com/ICTHoldingZERDE/govarch/invitations
