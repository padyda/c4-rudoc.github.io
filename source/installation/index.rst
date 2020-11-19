############
Установка
############

CodeIgniter4 можно установить разными способами: вручную, используя `Composer <https://getcomposer.org>`_, или `Git <https://git-scm.com/>`_. Как вам удобно?

- Если вы хотите просто "скачать и запустить", как это было с CodeIgniter3, выберите ручную установку.
- Если вы планируете использовать сторонние пакеты в проекте или легко обновлять  CodeIgniter, мы рекомендуем использовать установку через Composer.

.. toctree::
    :titlesonly:

    installing_composer
    installing_manual
    running
    upgrading
    troubleshooting
    repositories

Что бы вы не выбрали, `документация <https://codeigniter4.github.io/userguide/>`_ доступна онлайн.

.. note:: Перед использованием CodeIgniter 4, убедитесь, что ваш сервер соответствует :doc:`требованиям </intro/requirements>`, особо обратите внимание на версию PHP и его расширения. Возможно, придется раскомментировать некоторые строки в конфигурационном файле ``php.ini`` в разделе "extension", например, "curl" и "intl".
