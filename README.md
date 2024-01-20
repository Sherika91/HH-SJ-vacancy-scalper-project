# Program for collecting vacancies from HeadHunter.ru and SuperJob.ru
This is a small Project for educational reasons. It collects vacancies from Hh.ru and SuperJob.ru and saves them as a CSV file or JSON file.
it can collect vacancies from all pages or from a specific page count, search for vacancies by keywords, and also search for vacancies with a salary higher than the specified one.
Also, the program can collect vacancies by highest salary in search results that we input in search query.

# Приложение для сбора вакансий с сайта HeadHunter.ru и SuperJob.ru
Это небольшой проект из образовательных соображений. Он собирает вакансии из Hh.ru и SuperJob.ru и сохраняет их в виде файла CSV или JSON.
Он может собирать вакансии со всех страниц или с определенного количества страниц, искать вакансии по ключевым словам, а также искать вакансии с зарплатой выше указанной.
Также программа может собирать вакансии по самой высокой зарплате в поисковой выдаче, которую мы вводим в поисковый запрос.

# Before you start
make sure do obtain API keys from [SuperJob.ru](https://api.superjob.ru/)

## Installation
Before you start, make sure you have Python 3.7^ and pip installed on your system.
```
python --version
pip --version
```
If you don't have them, you can download them from [here](https://www.python.org/downloads/).

## Setup
### Clone the repository and navigate to the project directory.

```sh
git clone <project_url>
cd <skymakret>
```

### Create a virtual environment and activate it.
```sh
python -m venv venv
source venv/bin/activate
```

### Install requirements
```sh
pip install -r requirements.txt
```
### Set up your .env variables using .env.example file
```sh
cp .env.example .env
```