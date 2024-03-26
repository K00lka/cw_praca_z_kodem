# Instalacja paczek z pliku requirements.txt
make test
# Uruchomienie lokalnego serwera flask (plus instalacja jak w komendzie wyżej)
make run
# Sprawdzenie poprawności kodu w pythonie
make check
# Dzialanie serwera
Po wejściu na [stronę główną](http://127.0.0.1:5000) jesteśmy przywitani przez napis "Welcome to Flaskblog". Po wejściu na [podstronę hello](http://127.0.0.1:5000/hello) otrzymujemy komunikat Hello World. Jeżeli po tym linku podamy dodatkowo po slashu jakieś imię, komunikat zmieni się na "Hello <name>"