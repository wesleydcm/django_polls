# Instruções:

## Crie o ambiente virtual

```
python -m venv venv
```

## Ative o venv

```
# linux:
source venv/bin/activate
```
```
# windows:
.\venv\Scripts\activate
```

## Instale as dependências

~~~
pip install -r requirements.txt
~~~

## Execute as migrações
~~~
python manage.py migrate
~~~

## Execute o server
~~~
python manage.py runserver
~~~

