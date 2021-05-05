# Telegram бот по поиску вакансий в Москве

Данный бот предлагает на выбор профессию, по которой осуществляется поиск вакансий
на сайте *https://www.superjob.ru*

Чтобы запустить бот, необходимо в консоли прописать следующие команды:
``` bash
git clone https://github.com/khoribz/review2.git -b dev
cd review2
pip3 install -r requirements.txt
python3 bot.py;
```
Теперь можно найти в Telegram бота @GetVacancyBot и искать себе работу)


# Файлы проекта:
_bot.py_ - файл, в котором находятся основные функции, использующиеся при взаимодействии с ботом
_parse.py_ - файл, в котором происходит поиск информации о вакансиях в зависимости от выбранной профессии
_const.py_ - файл, в котором содержатся глобальные переменные
_jobs_name.py_ - файл, в котором находится словарь из профессии и ее части адреса на сайте
