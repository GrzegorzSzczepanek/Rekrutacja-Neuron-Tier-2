# Rekrutacja Neuron - Tier 2

## Cele

W tym rozwiązaniu macie spore pole do działań, a są tak dobrane by nie narzucać wam metody ich rozwiązania. Jednak jest kilka rzeczy, których oczekujemy:

- EDA - https://en.wikipedia.org/wiki/Exploratory_data_analysis
- Wytrenowanie klasyfikatora, a najlepiej kilku klasyfikatorów, by zobaczyć jakie rozwiązanie radzi sobie najlepiej. Preferowalnie w PyTorch, gdy zdecyfujecie się na sieci Neuronowe, poniewaz głównie z niego korzystamy w projektach, ale wybór jest wasz.
- Modularny kod, bo nie chcemy wszystkiego w jednym notebooku.
- Prezentacja wyników w Notebooku.

Warto tez README potraktować jako wizytówkę waszego projektu i miejsce, gdzie zamieścicie instrukcje jak uruchomić wasz kod.

## Ocena

Po pierwsze stwórzcie sobie prywatne repo i zaproście mnie (nick na gitubie i email macie) do niego, bym mógł mieć dostęp do waszych rozwiązań.
Pierwszorzędne znaczenie ma wasze podejście do problemu, jakość kodu, oraz EDA. Wyniki nie będą miały znaczenia przy ocenie.

## Informacje o danych

- Celem datasetu jest autentykację uytkownika na podstawie fal EEG.
- Uzytkownik był wystawiany na dwa typy bodźców wizualnych: znanych mu, oraz nieznanych.
- Informacja o tym, czy bodziec był znany jest zapisana w kolumnie `Flag`.
- Dane zostały wstępnie przetworzone przez średnią kroczącą o wielkości okna 5.
- Autentykacja użytkownika ma nastąpić tylko wtedy, gdy jego mózg zareaguje na przypisany do niego obrazek w sposób wskazujący, że już go wcześniej widział
- Dane zostały zebrane na urządzeniu [MindWave Mobile 2](https://neurosky.com/biosensors/eeg-sensor/)
- Dokumentacja [urządzenia](https://developer.neurosky.com/docs/doku.php?id=mindwave)

## Kontakt

W razie jakichkolwiek pytań mozna pisać śmiało.

- Discord: `grzes_451`
- Email: `grzegorzszczepanek48@gmail.com`
