# OHLCV-Server
OHLCV Server

How to install ?

1.Postgresql server
In postgresql-server : docker-compose up -d

Create an virtual environnement
python -m venv ohlcv-server

install packages
pip install -f requirement.txt

CREATE DATABASE ohlcv_backpack;
GRANT ALL PRIVILEGES ON DATABASE ohlcv_binance TO admin;
