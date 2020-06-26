# Reportistica sul mondo delle criptovalute 

Semplice progetto che prende delle informazioni sulle cripto valute e le salva in file JSON con le seguenti informazioni: 
1. La criptovaluta con il volume maggione (in $) delle ultime 24 ore.
2. Le migliori e peggiori 10 criptovalute (per incremento in percentuale delle ultime 24 ore).
3. La quantità di denaro necessaria per acquistare una unità di ciascuna delle prime 20 criptovalute.
4. La quantità di denaro necessaria per acquistare una unità di tutte le criptovalute il cui volume delle ultime 24 ore sia superiore a 76.000.000$ 
5. La percentuale di guadagno o perdita che avreste realizzato se aveste comprato una unità di ciascuna delle prime 20 cripto valute* il giorno prima (ipotizzando che la classifica non sia cambiata)

Per evitare che il programma sovrasriva lo stesso file JSON, viene denominato con la data del momento in cui il programma viene eseguito. 

*Le prime 20 criptovalute secondo la classifica predefinita di CoinMarketCap, quella visibile sul sito, dunque ordinate per capitalizzazione. 