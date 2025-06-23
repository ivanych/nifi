Инстанс NiFi для учебных целей.

Перед запуском нужно создать файл **.env** с некоторыми переменными:

    HOST_NIFI_WEB_HTTPS_PORT=8443
    CONTAINER_NIFI_WEB_HTTPS_PORT=8443
    SINGLE_USER_CREDENTIALS_USERNAME=
    SINGLE_USER_CREDENTIALS_PASSWORD=

Пароль должен быть минимум 12 символов, иначе NiFi будет генерировать
случайные логин и пароль.
