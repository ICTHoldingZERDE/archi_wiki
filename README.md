# Установка Archi

1. Установить Archi - инструмент для создания и управления архитектурными моделями.

https://www.archimatetool.com/download/

2. Установить CoArchi plugin - плагин для Archi для совместной работы с архитектурными моделями. Устанавливается через меню Help - Manage Plug-ins.

https://www.archimatetool.com/plugins/

3. В Archi в настройках в главном меню (Edit - Preferences - Collaboration) заполнить Name и Email (будут использоваться для идентификации сотрудника в журнале изменений архитектурных моделей).

4. С помощью блокнота (Notepad, Notepad++, VS Code) добавить в файл .gitconfig (находится в C:\Users\\{наименование учетной записи}) следующий код (не затирая имеющийся!):

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

5. Зарегистрироваться на github.com

6. Сгенерировать усиленный пароль по ссылке https://github.com/settings/tokens и сохранить на компьютере в текстовом файле (где удобно, обычно на рабочем столе). При генерации задайте произвольное название, бессрочное действие пароля и отметьте галочками все права.

7. Направить на почту mirambek.mustafin@zerde.gov.kz свой логин на github.com для получения приглашений для совместной работы над архитектурными моделями.

## По вопросам настройки Archi и доступа к github.com писать на почту mirambek.mustafin@zerde.gov.kz.
    
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
