![YAMDB banner](/static/%D0%91%D0%B5%D0%B7%20%D0%B8%D0%BC%D0%B5%D0%BD%D0%B8-1.jpg)
# REST API для сервиса YaMDb — базы отзывов о фильмах, книгах и музыке. (Совместный проект студентов Яндекс.Практикум)

Проект YaMDb собирает отзывы (*Review*) пользователей на произведения (*Title*). Произведения делятся на категории: «Книги», «Фильмы», «Музыка». Список категорий (*Category*) может быть расширен (например, можно добавить категорию *«Изобразительное искусство»* или *«Ювелирка»*).

Сами произведения в YaMDb не хранятся, **здесь нельзя посмотреть фильм или послушать музыку**.

В каждой категории есть произведения: книги, фильмы или музыка. Например, в категории «Книги» могут быть произведения «Винни Пух и все-все-все» и «Марсианские хроники», а в категории «Музыка» — песня «Давеча» группы «Насекомые» и вторая сюита Баха. Произведению может быть присвоен жанр из списка предустановленных (например, «Сказка», «Рок» или «Артхаус»). Новые жанры может создавать только администратор.

Благодарные или возмущённые читатели оставляют к произведениям текстовые отзывы (*Review*) и выставляют произведению рейтинг (оценку в диапазоне от одного до десяти). Из множества оценок автоматически высчитывается средняя оценка произведения.

## Подготовка к работе:

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
1. Клонируйте репозиторий на локальную машину.
- ``git clone https://github.com/KorsakovPV/api_yamdb.git``


### Необходимые компоненты Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you have to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc





![YAMDB banner](/static/%D0%91%D0%B5%D0%B7%20%D0%B8%D0%BC%D0%B5%D0%BD%D0%B8-1.jpg)

___

# REST API для сервиса YaMDb — базы отзывов о фильмах, книгах и музыке. (Совместный проект студентов Яндекс.Практикум)

Проект YaMDb собирает отзывы (*Review*) пользователей на произведения (*Title*). Произведения делятся на категории: «Книги», «Фильмы», «Музыка». Список категорий (*Category*) может быть расширен (например, можно добавить категорию *«Изобразительное искусство»* или *«Ювелирка»*).

Сами произведения в YaMDb не хранятся, **здесь нельзя посмотреть фильм или послушать музыку**.

В каждой категории есть произведения: книги, фильмы или музыка. Например, в категории «Книги» могут быть произведения «Винни Пух и все-все-все» и «Марсианские хроники», а в категории «Музыка» — песня «Давеча» группы «Насекомые» и вторая сюита Баха. Произведению может быть присвоен жанр из списка предустановленных (например, «Сказка», «Рок» или «Артхаус»). Новые жанры может создавать только администратор.

Благодарные или возмущённые читатели оставляют к произведениям текстовые отзывы (*Review*) и выставляют произведению рейтинг (оценку в диапазоне от одного до десяти). Из множества оценок автоматически высчитывается средняя оценка произведения.

___

## Установка:
1. Клонируйте репозиторий на локальную машину.
- ``git clone https://github.com/KorsakovPV/api_yamdb.git``
2. Установите виртуальное окружение.
- ``python3 -m venv venv``
3. Активируйте виртуальное окружение.
- ``source venv/bin/activate``
4. Установите зависимости.
- ``pip install -r requirements.txt``
5. Запустите локальный сервер.
- ``python manage.py runserver``
6. Перейдите в документацию проекта.
- **[REDOC](http://127.0.0.1:8000/redoc/)**

___

## Над проектом работали:
**[Павел Корсаков](https://github.com/KorsakovPV)**. Управление пользователями: система регистрации и аутентификации, права доступа, работа с токеном, система подтверждения e-mail, поля.

**[Владимир Самородов](https://github.com/Jejevkin)**.  Категории, жанры и произведения: модели, view и эндпойнты для них.

**[Олег Завитаев](https://github.com/TheZavitaev)**. Отзывы и комментарии: модели и view, эндпойнты, права доступа для запросов. Рейтинги произведений.
