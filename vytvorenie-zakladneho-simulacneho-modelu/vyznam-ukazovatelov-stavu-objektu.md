# Význam ukazovateľov stavu objektu

Objekty simulačného modelu sa môžu nachádzať v určitom prevádzkovom stave. Napr. objekt materiálového toku Station sa môže nachádzať v stave, že pracuje, čaká , je blokovaný atď. Stav týchto objektov je možné ukazovať pomocou zmeny ikony alebo pomocou farebných ukazovateľov ktoré sa zobrazujú pri ikone daného objektu. Zobrazovanie stavov pomocou ukazovateľov a zobrazovanie materiálového toku je možné zapnúť alebo vypnúť na Ribon bare na paneli Home v časti Animations tlačidlami MUs a Icons, ako ukazuje obrázok.

<figure><img src="../.gitbook/assets/ukazovatele_objektu.png" alt=""><figcaption><p>Zmena stavov ukazovateľov objektov</p></figcaption></figure>

Základný význam jednotlivých stavov objektov sumarizuje tabuľka:

|                    |                                                                          |                  |
| ------------------ | ------------------------------------------------------------------------ | ---------------- |
| Stav objektu       | Uážka                                                                    | Farba Indikátora |
| Blokované          | <img src="../.gitbook/assets/image (6).png" alt="" data-size="original"> | Žltá             |
| Závada             | ![](../.gitbook/assets/image.png)                                        | červená          |
| Pauza              | ![](<../.gitbook/assets/image (8).png>)                                  | modrá            |
| ZapínanieVypínanie | ![](<../.gitbook/assets/image (1).png>)                                  | fialová          |
| Reštartovanie      | ![](<../.gitbook/assets/image (10).png>)                                 | tyrkysová        |
| Nastavovanie       | ![](<../.gitbook/assets/image (7).png>)                                  | hnedá            |
| Zastavovanie       | ![](<../.gitbook/assets/image (4).png>)                                  | ružová           |
| Neplánované        | ![](<../.gitbook/assets/image (5).png>)                                  | slabo modrá      |
| Čakanie            | ![](<../.gitbook/assets/image (2).png>)                                  | oranžová         |
| Práca              | ![](<../.gitbook/assets/image (9).png>)                                  | zelená           |

V prípade nášho jednoduchého modelu je možné vidieť len stav Práca (zelený indikátor) kedy stanica vykonáva činnosť a stav Blokovanie (žltý indikátor) kedy objekt Source čaká na to kým stanica vykoná prácu a uvoľni miesto pre ďalšie MU ktoré sa bude spracovávať.

