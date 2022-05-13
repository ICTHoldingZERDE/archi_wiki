# Настройка инструментария для создания и управления архитектурными моделями

1. Установить Archi - инструмент для создания и управления архитектурными моделями.

https://www.archimatetool.com/download/


2. Установить CoArchi plugin - плагин для Archi для совместной работы с архитектурными моделями. Устанавливается через меню Help - Manage Plug-ins.

https://www.archimatetool.com/plugins/

![изображение](https://user-images.githubusercontent.com/5103438/168207862-b17f2d83-89b7-4dc3-a0cf-8abf9124273a.png)


3. В Archi в настройках в главном меню (Edit - Preferences - Collaboration) заполнить Name и Email (будут использоваться для идентификации сотрудника в журнале изменений архитектурных моделей).

![изображение](https://user-images.githubusercontent.com/5103438/168208122-452b3a9f-a6dc-4c41-8c5c-389317f08ce3.png)

4. В Проводнике включить отображение скрытых файлов:

![изображение](https://user-images.githubusercontent.com/5103438/168208284-2482d9bf-6b98-4766-a069-e32782ab4ff4.png)


5. С помощью блокнота (Notepad, Notepad++, VS Code) добавить в файл .gitconfig (находится в C:\Users\\{наименование учетной записи}) следующий код (не затирая имеющийся!):

1)

![изображение](https://user-images.githubusercontent.com/5103438/168208420-58c1b9f1-dbf8-4ed7-a101-faac6ac24839.png)

2)
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

![изображение](https://user-images.githubusercontent.com/5103438/168208560-dfdbc1e6-4a5d-44cc-bd0b-7e90e4fbaae4.png)


5. Зарегистрироваться на github.com

6. Сгенерировать усиленный пароль по ссылке https://github.com/settings/tokens 

![изображение](https://user-images.githubusercontent.com/5103438/168208720-42370c12-e3bb-4233-a12f-318d083fd34e.png)

При генерации задайте произвольное название, бессрочное действие пароля и отметьте галочками все права.

![изображение](https://user-images.githubusercontent.com/5103438/168208852-7314ff03-90c9-44fb-b89c-4944fe9e37d6.png)

7. Сохранить сгенерированный пароль на компьютере в текстовом файле (где удобно, обычно на рабочем столе).

![изображение](https://user-images.githubusercontent.com/5103438/168208930-1882395a-e0d9-48c7-828a-4bf0ddfcb769.png)

8. Уточните у ответственного лица вашего структурного подразделения наименование проекта, с которым будете работать, и направьте на почту mirambek.mustafin@zerde.gov.kz и kairat.zholboldin@zerde.gov.kz свой **логин** (не почту!!!) на github.com и наименование проекта соответственно для получения приглашений для совместной работы над архитектурными моделями.

Логин указан здесь:

![изображение](https://user-images.githubusercontent.com/5103438/168209199-0098b24f-ed2b-427a-9504-a1eee577fc1e.png)


9. После предоставления доступа на почту, указанную при регистрации на github.com, придет соответствующее уведомление. Необходимо принять приглашение и направить запрос на дальнейшую настройку на почту mirambek.mustafin@zerde.gov.kz и kairat.zholboldin@zerde.gov.kz. 

## По вопросам настройки Archi и доступа к github.com писать на почту mirambek.mustafin@zerde.gov.kz и kairat.zholboldin@zerde.gov.kz.
    
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
