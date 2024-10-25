<center>
<img src="./.docs/assets/banner.png">
</center>

# О проекте
ClientGuardian - проект разработанный специально для ОАО "РЖД", нацеленный на формирование прогнозной модели оттока действующих клиентов. 

# Проблема
На сегодняшний день аналитика по модели перспективного поведения клиентов (увеличение/уменьшение грузоперевозок, увеличение/уменьшение доходов) прорабатывается вручную на основании доступной информации. При текущей организации процесса не предоставляется возможным формирование новой бизнес-модели работы сотрудника с учётом минимизации рутинных процессов и подготовки предиктивных мероприятий, направленных на удержание действующих клиентов .

# Как пользоваться?
- ## Установка зависимостей
    1. [Установите pyenv](https://github.com/pyenv-win/pyenv-win/blob/master/docs/installation.md) 
    2. Установите python 3.10 `pyenv install 3.10`
    3. Сделайте эту версию глобальной `pyenv global 3.10`
    4. [Установите poetry](https://github.com/python-poetry/install.python-poetry.org/blob/main/README.md) 
    5. Войдите в виртуальное окружение: `poetry shell`
    6. Установите зависимости: `poetry install`

- ## Запуск
    - Если вы еще не вошли в виртуальное окружение, - сделайте это `poetry shell`
    - Запустите главный модуль - `python src/app.py`


# Вклад в развитие
Вклад в развитие ClientGuardian приветствуется! Если вы обнаружите какие-либо проблемы или у вас есть идеи по улучшению, не стесняйтесь открывать проблему или отправлять запрос на слияние.

# Лицензия
ClientGuardian распространяется под лицензией MIT. \
Подробнее смотрите в файле [LICENSE](LICENSE).