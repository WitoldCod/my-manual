# Podręcznik git/github na mój własny użytek

1. Dodanie zmian w całym repozytorium:
- git add -A
- git commit -m "komentarz do rewizji"

2. instalacja starszej wersji pythona
\# (działa w ubuntu 20.0 w 18.04 nie działa)
- Dodaj repozytorium deadsnakes PPA:
- 'sudo add-apt-repository ppa:deadsnakes/ppa'
- Zaktualizuj listę pakietów:
- 'sudo apt-get update'
- Zainstaluj Pythona 3.5 (lub wyżej nizszych wersji nie ma na serwerze deadsnakes):
- 'sudo apt-get install python3.5'

3. Insatalcja virtualenv:
'''
sudo apt-get update
sudo apt-get install virtualenv
'''

4. Utworzenie środowiska wirtualnego:
'virtualenv -p /usr/bin/python3.5 venv35'

5. Uruchomienie środowiska wirtualnego:
- 'source venv35/bin/activate'

6.Deaktywacja środowiska wirtualnego:
- 'deactivate'