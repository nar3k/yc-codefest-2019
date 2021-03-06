# Использование Yandex.Cloud Translate API и Python

Здравствуйте! В этом примере мы научимся использовать облачный сервис для перевода текста при помощи API Яндекс.Облака и Python.


# Получение доступа к API

Есть два способа использования сервиса:

 1. При помощи токена авторизации,  при этом токен необходимо своевременно продлять.
 2. При помощи ключа API (им и воспользуемся)

## Как получить доступ?

 1. Откройте в браузере консоль Яндекс.Облака: https://console.cloud.yandex.ru/
 2. Перейдите в созданный для мероприятия каталог
 3. Откройте на вкладке слева раздел "Сервисные аккаунты"
 4. Нажмите кнопку создать новый ключ, и в выпадающем списке выберите тип "Создать API -ключ"
 5. Скопируйте или лучше сохраните в текстовый файл получившийся ключ.

## Тестирование сервиса

1. Откройте Jupyter Notebook "Translate-Scale", расположенный по адресу [http://84.201.157.101:8888/notebooks/my_project_dir/my_project_env/Translate.ipynb](http://84.201.157.101:8888/notebooks/my_project_dir/my_project_env/Translate.ipynb)
 (подставьте токен доступа - 4831fad7cc6b83a8dca2a117960b1e77ef8f07ee44f84669)
2. Подставьте в 6-й строке сверху в поле заголовков HTTP ('Api-Key //ваш ключ//') ваш API-ключ.
3. Обратите внимание на переменную mytext - в ней вы можете задать свой произвольный текст для перевода
4. Обратите внимание на параметры, передаваемые в body - sourceLanguageCode и targetLanguageCode, можете поменять их на свое усмотрение. Описание возможных параметров доступно тут
[https://cloud.yandex.com/docs/translate/api-ref/Translation/translate](https://cloud.yandex.com/docs/translate/api-ref/Translation/translate)
3. Выполните ячейку - (для этого нажмите Shift+Enter 
## Поздравляем, у вас все получилось!


```
