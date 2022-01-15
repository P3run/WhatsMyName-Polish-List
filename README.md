# WhatsMyName-Polish-list

## PL

Niniejsze repozytorium zawiera alternatywną listę serwisów kompatybilną z projektem [WhatsMyName](https://github.com/WebBreacher/WhatsMyName) i służy do wyszukiwania profili użytkowników w polskich serwisach.

### Konfiguracja i użytkowanie
1. Pobierz i zainstaluj [Pythona](https://www.python.org/downloads/) w wersji 3.x.x
2. Pobierz projekt [WhatsMyName](https://github.com/WebBreacher/WhatsMyName).
3. Otwórz główny folder projektu i zainstaluj zależności:
    ```
    $ pip3 install -r requirements.txt
    ```
4. Pobierz polską listę i umieść w głównym folderze projektu.
5. Uruchom skrypt `web_accounts_list_checker.py` pamiętając o użyciu flag / argumentów:
    + `-f` - podążanie za przekierowaniami
    + `-in` - w celu zdefiniowania listy innej niż domyślna
    + `-u` - w celu zdefiniowania szukanego loginu
    ```
    $ python3 ./web_accounts_list_checker.py -f -in web_accounts_list_pl.json -u Neo
    ```
6. Poczekaj na wyniki!

---

## ENG

This repository contains an alternative list of websites compatible with the WhatsMyName project and is used to search for user profiles on Polish websites.

### Configuration and usage
1. Download and install [Python](https://www.python.org/downloads/) ver. 3.x.x
2. Download [WhatsMyName](https://github.com/WebBreacher/WhatsMyName).
3. Open the main project folder and install the dependencies:
    ```
    $ pip3 install -r requirements.txt
    ```
4. Download Polish list and put it into the main folder of WhatsMyName.
5. Run the script `web_accounts_list_checker.py` remembering to use the following flags / arguments:
    + `-f` - following redirects
    + `-in` - to specify a list other than the default
    + `-u` - to specify the login you are looking for
    ```
    $ python3 ./web_accounts_list_checker.py -f -in web_accounts_list_pl.json -u Neo
    ```
6. Wait for the results!

# License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.