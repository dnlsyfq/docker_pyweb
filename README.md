
* Setup MAC
```
python3 -m venv venv
. venv/bin/activate
```

* Module Installation
```
pip install fastapi
pip install uvicorn
```

* Run
```
uvicorn main:app --reload
```

@ 

```
python main.app
```

* Dockerize 
```
# root directory
pip freeze > requirements.txt
```

* Build image

```
docker build -t python-fastapi .
docker run python-fastapi

```

```
docker run -p 8000:8000 python-fastapi
```