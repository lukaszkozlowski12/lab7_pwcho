# Zadanie pwcho_lab7

## Polecenie:

W tym zadaniu należy zbudować prosty plik docker-compose.yml, który
pozwoli na uruchomienie znanej z innych zajęć, uslugi LAMP. 
Usługa ta składa się z trzech usług składowych:
- serwera Apache 
- serwera PHP 
- bazy danych MySQL

## Założenia:

1.Serwery są budowane zgodnie z dokumentacją obrazów bazowych dostępnych na
DockerHub i umieszczonych tam plików Dockerfile,
2.Serwery PHP i MySQL są przyłączone do sieci backend, a Apache do backend oraz
frontend. Apache ma wystawiony na świat zewnętrzy port 6666.

### Uruchamianie:

```bash docker-compose up ```

### Zatrzymanie:

```bash docker-compose down ```
