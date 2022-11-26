Что бы получить список пакетов в проекте

''''python
pip freeze
''''
Для записи вывода в requirements.txt
дополняеем следущим образом :

''''python
pip freeze > requirements.txt
''''

Запуск инициализации библиотек на requirements.txt:

''''
pip install -r requirments.txt

''''