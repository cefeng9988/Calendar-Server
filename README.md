# CalendarApp (Team 20)

## App Repo
This repository is coupled with the following repository for the front-end: https://github.com/cefeng9988/Calendar-Application

## Installation

Setup postgresql and .env vars

```
pip3 install -r requirements.txt
```

## Quickstart

```python
python3 app.py
```

Check Server Activity
```python
	psql cs411
	SELECT * FROM invite;
	\q   
	```
	//to exit

## Database migration folder commands

Init migration folder

```
flask db init
```

Create migration

```
flask db migrate -m "Initial migration."
```

Commit migration

```
flask db upgrade
```
