# Baseline — pomiar stanu wyjściowego

Plik uzupełniasz w ZADANIU 01. Czasy odczytujesz w zakładce **Actions**. Wystarczy dokładność
do sekundy.

## Czasy kroków — przebieg na `main`

| Krok | Czas |
|---|---|
| Set up job | 1 s |
| Checkout | 1 s |
| Set up Node | 0 s |
| Install dependencies | 5 s |
| Install Playwright browsers | 19 s |
| Unit tests | 1 s |
| API tests | 19 s |
| UI tests | 2 m 25 s|
| Upload Playwright report | 2 s |
| Post Set up Node | 0 s |
| Post Checkout | 0 s |
| Complete job | 0 s |
| **Cały przebieg** | 3 m 16 s |

## Czas do pierwszego czerwonego sygnału

| Branch | Czas samego testu | Od startu przebiegu do informacji o błędzie |
|---|---|---|
| `demo/failing-unit` | 1s | 26s |
| `demo/failing-search` | — | 4m 8s |

Co na `demo/failing-unit` stało się z testami API i UI:

## `demo/failing-lint` i `demo/failing-security`

| Branch | Wynik przebiegu | Dlaczego tak |
|---|---|---|
| `demo/failing-lint` | | |
| `demo/failing-security` | | |

## Pięć problemów obecnego pipeline’u

1.
2.
3.
4.
5.

## Pomiary z kolejnych zadań

Tu dopisujesz pomiary i odpowiedzi z kolejnych zadań, pod nagłówkiem z numerem zadania.
