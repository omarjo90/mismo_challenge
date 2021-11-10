Run the API
```sh
cd api
pipenv install
pipenv shell
python init-db.py
flask run
```
Run frintend
```sh
cd web
yarn install
yarn start
```

Run the test cases
```sh
cd tests/
pytest -v
```
