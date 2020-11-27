# docker-compose
Ten projekt składa się z pliku docker-compose.yaml, który używa plik Dockerfile w celu uruchomienia serwera php-apache i bazy danych mysql.
Uruchamiamy to za pomocą
```
sudo docker-compose up -d
```
Celem poniższej komendy jest przesłanie danych przez adres URL 
```
curl http://localhost:6666/
```

