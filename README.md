# Birthday checcker

All the actions described here should be made inside repo, so here how can it be done
```bash
git clone https://github.com/korney4eg/my_tests
cd my_tests
```

## How to run

To run it following steps should be made:

0. Go to `1.Hello_World_app/` folder
```bash
cd 1.Hello_World_app/
```

1. configuration file `.db_config.ini` created, that contains database connection info.

Here is example
```ini
[database]
host = 127.0.0.1
port = 3306
database = my_users
user = myuser
password = 12345678
```

2.  database should be running

To simplify just run docker compose command:
```bash
docker-compose up -d
```

3. requirements should be installed

```bash
pip install -r requirements.txt
```

4. run programm

```bash
python main.py
```
