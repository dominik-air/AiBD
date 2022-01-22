## Repozytorium podzielone jest zgodnie z TIER Protocol na foldery:
- Original Data zawierającego pierwotne dane przed wyczyszczeniem oraz podfolder Metadata z opisem informacji zawartych w zbiorze danych
- Analysis Data zawierającego dane w formie tidy data
- Command Files zawierającego skrypty do wyczyszczenia oraz analizy danych
- Documents zawierającego Data Appendix oraz Final Paper

## Modyfikacje dokonane na pierwotnych danych:
- brakujące dane w kolumnie 'Wiek kupującego' zostały uzupełnione medianą wieku w tej kolumnie

## Jak powtórzyć badania:
1. Uruchomić skrypt data_tidier.ipynb w celu wyczyszczenia danych pierwotnych.
2. Uruchomić skrypt analysis.ipynb w celu odtworzenia wykresów zawartych w Final Paper i Data Appendix.
3. Przeanalizować ponownie czy przeprowadzone przeze mnie badania odpowiadają na 3 postawione wcześniej pytania dotyczące zbioru danych.