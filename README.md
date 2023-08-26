### Instalar y usar

```bash
cd ShopZone/ShopZone
```

```bash
python3 -m venv env
source env/bin/activate
```

```bash
pip install -r requirements.txt
```

```bash
mkdir dist
mkdir dist/static
```

```bash
python3 manage.py createsuperuser
```

```bash
python3 manage.py runserver
```
### En una nueva terminal
```bash
cd frontend
npm i
npm run dev
```
#### Abre la siguiente url e inicia session con el usuario que creaste con Django
<a href="http://localhost:5173/">http://localhost:5173/</a>