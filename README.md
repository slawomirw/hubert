# Hubert projekt

## Instalacja oprogramowania:

Zainstaluj GIT pobierając plik z (https://git-scm.com/download/win).

## Praca z repozytorium

### Uruchom program GIT CMD

### Przygotowanie projektu 

  > mkdir hubert-projekt <enter>
  
  > cd hubert-projekt <enter>
  
  > git clone https://github.com/slawomirw/hubert.git <enter>
  
  > cd hubert <enter>
  
  > dir <enter>

### Przygotowanie zadania

  > mkdir zadanie1
  
  > cd zadanie1
  
  > echo "\<head\>\<\/head\>\<body\>\<\/body\>" \>\> index.html
  
  > git add .
  
  > git config --global user.email "adres@email"

### Założenie konta GitHub
  
  Wejdź na https://github.com/ i wybierz [Sign Up]. Podaj adres email oraz nowe hasło.
 
### Zapisanie dodanych/zmienionych plików

  > git add .
  
  > git commit -m "opis zmiany"
  
  > git push -u origin master
  
### Pobranie zmian z serwera

  > git pull
 
