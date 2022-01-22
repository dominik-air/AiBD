# Final paper
## Analiza zbioru danych 12_S╠üWIE╠ĘTOKRZYSKIE.csv
### Histogramy:

![Histogram 0](data_appendix_hist0.png "Histogram 0")
![Histogram 1](data_appendix_hist1.png "Histogram 1")
![Histogram 2](data_appendix_hist2.png "Histogram 2")
![Histogram 3](data_appendix_hist3.png "Histogram 3")

### Jaka jest mediana ocen każdej z marek odkurzaczy?

![Median](data_appendix_median_vaccum_rating.png "Mediana")

Można zauważyć, że najwyższe oceny pod względem mediany mają odkurzacze marki Electrolux oraz Beko, ale poza tym to generalnie są one całkiem pododbne. Użytecznym zatem będzie również sprawdzenie jak prezentuje się rozkład ocen dla każdej z marek odkurzaczy.

![Boxplot 0](data_appendix_dist_vaccum_rating.png "Boxplot 0")

Jak można zauważyć Beko pomimo jednej z najwyższych median ocen ma dosyć szeroką rozpiętość ocen z lekkim przekrzywieniem w stronę tych słabszych ocen. Dla porównania Samsung jest mocniej przekrzywiony w stronę lepszych wartości ocen. Przyczyną takiego rozkładu ocen w przypadku odkurzaczy Beko, czy też Dyson może być pewna stronniczość klientów(ktoś nie lubi marki X zatem da jej słabą ocenę albo zaznaczy najwyższą ocenę aby system zbierania feedbacku się od niego ‘odczepił’). Do rzetelniejszej analizy potrzebne by były na pewno treści recenzji, a nie jedynie oceny danego produktu.

### Jak różnią się oceny odkurzaczy ze względu na wiek?

![Boxplot 1](data_appendix_dist_vaccum_rating_by_age.png "Boxplot 1")

Współczynnik korelacji wieku kupującego i oceny odkurzaczy: -0.10152332751198487.
Można wskazać, że wraz z wiekiem odkurzacze oceniane są niżej. Świadczy o tym również współczynnik korelacji(co warto wspomnieć słabej). Analizę można rozszerzyć o sprawdzenie istnienia jakiejś nielinowej relacji między wiekiem kupującego, a oceną produktu. Z wykresu widać, że mediana ocen w poszczególnych grupach potrafi się różnić nawet o 1 stopień.

### Jak różnią się oceny odkurzaczy ze względu na płeć?

![Boxplot 2](data_appendix_dist_vaccum_rating_by_sex.png "Boxplot 2")

Można zaobserwować, że kobiety wyżej oceniały zakupione przez siebie odkurzacze w porównaniu do mężczyzn. Może być to spowodowane tym, że bardziej znają się na sprzęcie, którym na co dzień operują, zatem dokonywały trafniejszych zakupów. Możliwe, że wyżej oceniały zakupione odkurzacze, bo im ciężej przyznać się do błędu niż mężczyznom.