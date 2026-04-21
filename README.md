# -scooter-sharing

## Описание
Команда 22. Анализ сервиса аренды самокатов.  

### dashboard: https://datalens.yandex/9h4chhxxgw0it
### [Презентация](Презентация22.pdf)

## Clone repo

```bash
git clone https://github.com/Warghz/-scooter-sharing.git
cd -scooter-sharing.git
```

### Create and activate virualenv

``` bash
python3 -m venv .venv
source .venv/bin/activate  
```

### Install requirements

```bash
# prod requirements
pip install -r requirements/prod.txt  
# dev requirements
pip install -r requirements/develop.txt  
```

### Create .env

```bash
echo 'DATA_PATH=""' > .env
```
