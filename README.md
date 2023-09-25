<h1 align="center">Welcome to my Github! I am <a href="https://daniilshat.ru/" target="_blank">Alex</a> 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h4 align="right">May the testing be with you </h4>
  

#  Technologies and tools:


[<img src=https://user-images.githubusercontent.com/125588671/270274240-0b2a1a7a-58a1-4d02-85eb-f0490384cd7f.png height="68">](https://developer.chrome.com/docs/devtools/)
[<img src=https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg height="68">](https://www.python.org/) 
[<img src=https://user-images.githubusercontent.com/125588671/270273375-4f4ca48b-1302-431a-a02e-75ce20173789.svg height="68">](https://www.jetbrains.com/ru-ru/pycharm/)
[<img src=https://user-images.githubusercontent.com/125588671/270273298-7df7439a-85ec-401b-b4e4-10dd87113ead.svg height="68">](https://code.visualstudio.com/)
[<img src=https://user-images.githubusercontent.com/125588671/270274245-3a66a88f-2788-4cab-a0b8-b89863932bd3.png height="68">](https://docs.pytest.org/en/7.4.x//)
[<img src=https://user-images.githubusercontent.com/125588671/270274251-12f6bf28-419c-4c34-8b34-8f1c129cb61b.png height="68">](https://github.com/yashaka/selene)
[<img src=https://user-images.githubusercontent.com/125588671/270273340-0fe26f6c-0682-40e2-afcc-940e1571fb97.svg height="68">](https://github.com/aaoshepkov)
[<img src=https://user-images.githubusercontent.com/125588671/270273316-ffcef045-2e3b-4528-a211-baa16e5475f1.svg height="68">](https://www.postman.com/)
[<img src=https://user-images.githubusercontent.com/125588671/270274232-b1cbaabd-c2a7-4b2b-b3b4-c363ff62efaf.png height="68">](https://soapui.ru/)
[<img src=https://user-images.githubusercontent.com/125588671/270273394-79fb6e1a-e10c-4e8f-8fef-23a902eb6546.svg height="68">](https://swagger.io/)
[<img src=https://user-images.githubusercontent.com/125588671/270273370-5b4f24c6-187b-44eb-bd6e-fd035d819f05.svg height="68">](https://www.postgresql.org/)
[<img src=https://user-images.githubusercontent.com/125588671/270273366-773b75c3-9b8d-4eb1-9d31-ab3c2a358fba.svg height="68">](https://www.mysql.com)
[<img src=https://user-images.githubusercontent.com/125588671/270273337-e7e19966-0ab7-48af-853a-eaa3a1025c85.svg height="68">](https://www.atlassian.com/ru/software/confluence)
[<img src=https://user-images.githubusercontent.com/125588671/270273360-c7a2539e-3458-48c8-8830-93c87150438e.svg height="68">](https://www.atlassian.com/ru/software/jira)



# Проекты.  

***Проект 1: тест веб-приложения для учителей от Skyeng***

Что нужно было сделать:

Задача №1: Необходимо было протестировать работу раздела "Личные события" в календаре для преподавателей. Задача №2: Провести смоук, функциональное, регрессионное тестирования новой фичи. Как решал: проналализировал требования, оформил замечания. Написал тест-план в Confluence, составил чек-листы в Siechko и тест-кейсы в Qase.io. Затем ознакомился с работой функционала фичи через GUI, выписал вопросы. Прогнал тест - кейсы, сперва смоук, затем позитивные, после негативные, регресс. Найденные ошибки оформил в Jira.

[Вот ссылка на проект](https://courageous-saffron-3c5.notion.site/1-2-f0be1834812a4f6e971e840b8e4708e7?pvs=4)

Что в итоге: Итоговый проект условно готов к релизу, так как в одной из реализованных фич (для стейкхолдера Анастасия Петровна) реализовано добавление события в предыдущий месяц только одним из двух заявленных способов (только переходом к предыдущему месяцу в календаре и клике в слот нужной даты), а также отсутствует возможность установить дату из предыдущего месяца при редактировании ранее созданного события в календаре. Однако, заявленный функционал все же доступен конечному пользователю.

***Проект 2: тест кабинета учителя в приложении Skyeng***

Что нужно было сделать:

Задача №1: Протестировать новый функционал на бэкенде через API. Использовал Postman. Задача №2: Также провести приемочное тестирование с учетом интересов и требований стейк-холдеров. Как решал: ознакомился с требованиями стейк-холдеров, документацией по API. Скорректировал тест-план в Confluence, написал тест-кейсы в Qase.io чек-листы в Sitechko. Провел тесты в Postman, сохранил коллекцию для последующих тестов, результаты внес в Confluence, ошибки оформил в Jira.

[Ссылка на проект](https://courageous-saffron-3c5.notion.site/1-2-f0be1834812a4f6e971e840b8e4708e7?pvs=4)

Выводы (итоги): Тестирование API выявило 5 ошибок, среди которых одна может быть воспроизведена только через API запрос, через GUI воспроизвести эту ошибку нельзя. Ошибки не являются критическими. Одна из них указывает на возможность реализации дополнительного функционала - возможность установить любой цвет из палитры шестнадцатиричных цветов.

### Итог №1 Функцционал реализован согласно требованиям, есть одна ошибка с приоритетом Mid и серьезностью Minor. Согласно моему выводу, ошибку можно исправить после релиза в ходе эксплуатации.  
### Итог №2 Приемочное тестирование завершено успешно, новый функционал соответствует требованиям заказчиков и техническим требованиям.  
## Контактная информация  
Email: alex.osh444@gmail.com  
[LinkedIn](https://www.linkedin.com/in/aleksandr-oshchepkov-a63189b3/)

