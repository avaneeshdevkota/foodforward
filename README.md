# FoodForward

## Team Members

* [Aavishkar Gautam](https://github.com/aavishkar6)
* [Avaneesh Devkota](https://github.com/avaneeshdevkota)
* [Seolin Jung](https://github.com/seolinjung)
* [Soyuj Jung Basnet](https://github.com/basnetsoyuj)

## Product vision statement

See instructions. Delete this line and place the Product Vision Statement here.

## User stories

* [Issues](issues.txt)

## Task boards

* [Sprint 1](https://github.com/orgs/software-students-fall2023/projects/15/views/1?layout=board)
* [Sprint 2](https://github.com/orgs/software-students-fall2023/projects/35/views/1?layout=board)

## Setup

### MongoDB

- Copy the `.env.example` file contents to a new `.env` file and edit the details accordingly.
- Start the MongoDB server.

### Environment

Use Pipenv to manage dependencies. See [Pipenv](https://pipenv.pypa.io/en/latest/installation/) for details.

Install Pipenv:

```sh
pip install pipenv
```

Install dependencies:

```sh
pipenv install
```

Activate the virtual environment:

```sh
pipenv shell
```

Finally, run the flask app:

```sh
flask run --reload
```

### Filler Data

Filler data will be added automatically to the database if there is no data in the collections initially.

Run the following in the root directory if you need to manually add filler data to the database:

```sh
python -m scripts.fill
```