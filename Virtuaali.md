# Poetry
* Jos suoritamme tiedoston komentoriviltä komennolla: ``` python3 src/index.py ```
* ```poetry run```-komento siis suorittaa annetun komennon virtuaaliympäristössä, jonka sisällä Python löytää riippuvuutumme.
* ```poetry run python3 src/index.py```
***
* ```poetry shell``` on kätevintä olla koko ajan virtuaaliympäristön sisällä
* Virtuaaliympäristön sisällä voimme suorittaa komennon “normaalisti”, eli ilman ```run```-komentoa: ```python3 src/index.py```
* Voimme lähteä virtuaaliympäristöstä komennolla ```exit```.

python3 src/index.py
# Venv
* ```python3 -m venv venv```
* ```source venv/bin/activate```
* ```deactivate```
