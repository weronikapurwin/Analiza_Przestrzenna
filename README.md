Celem skryptu jest wyznaczenie obszaru pod budowę obiektu świadczącego usługi hotelarskie spełniającego 
ustalone kryteria.

Kryteria:
| Lp. | Kryteria | Parametry | Źródło Danych |
| --- | --- | --- | --- |
| 1 | odległość od konkurencji | minimum 400m | BDOT10K |
| 2 | odległość od budynków mieszkalnych | od 25 do 150m | BDOT10K |
| 3 | odległość od istniejących dróg | od 15 do 100 m | BDOT10K |
| 4 | odległość od rzek i zbiorników wodnych | nieprzekraczalna strefa ochronna poniżej 20m | BDOT10K |
| 5 | pokrycie terenu | nie w lesie | BDOT10K |
| 6 | nachylenie stoków | maksymalnie 20 % | NMT |
| 7 | dostęp światła słonecznego | toki południowe (SW-SE) | NMT |
| 8 | poza strefą ochronną gazociągu | minimum 25 m | zasób prowadzącego |
| 9 | użytkowanie terenu | Nie ‘G’, ‘E’, ‘M’, ‘T’, ‘F’, ‘Fb’, ‘Fc’, ‘FG’ | Baza danych glebowo-rolnicza |
| 10 | przydatne działki → obszary | 1 - 6 ha | EGiB |
| 11 | kształt obszaru | jak najbardziej zwarty | - |

W skrypcie zastosowano dwa podejścia:
- kryteria otrzymują równe wagi podczas łączenia.
- kryteria otrzymują różne, ustalone wagi podczas łączenia.

Przykładowy wynik selekcji działki dla wag o równych wagach z najbardziej zwartym kształtem:

![image](https://user-images.githubusercontent.com/92334838/224555388-ac67948a-c5f2-4e54-80a5-61c1123d7e92.png)

