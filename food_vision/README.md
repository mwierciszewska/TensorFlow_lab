# Food Vision – Image Classification with TensorFlow

## Cel projektu
Celem projektu było zbudowanie modelu Deep Learning do klasyfikacji obrazów jedzenia
z wykorzystaniem sieci konwolucyjnych oraz transfer learning.

## Dane
- Obrazy przedstawiające różne klasy jedzenia
- Dane zostały podzielone na zbiór treningowy i walidacyjny

## Model
- Architektura: CNN + transfer learning
- Pretrained model: MobileNetV2
- Framework: TensorFlow / Keras

## Proces
1. Wczytanie i przygotowanie danych
2. Augmentacja obrazów
3. Feature extraction z wykorzystaniem MobileNetV2
4. Trening modelu
5. Ocena jakości modelu

## Wyniki
- Model poprawnie rozpoznaje większość klas
- Największe błędy pojawiają się między wizualnie podobnymi klasami

## Wnioski
Projekt pozwolił na praktyczne poznanie:
- działania sieci CNN
- mechanizmu transfer learning
- procesu trenowania i walidacji modeli DL