# covid19_ard

## ARD Stories on Covid19 


- NDR about Johns Hopkins data soruces
https://www.tagesschau.de/inland/johns-hopkins-uni-corona-zahlen-101.html

- BR using Insta-Infos to see where Ischgl tourists went
https://www.br.de/nachrichten/deutschland-welt/coronavirus-von-ischgl-quer-durch-europa,RuqCj62

- BR explorable explanation of corona spreading
https://web.br.de/interaktiv/corona-simulation/



## Pooling of ARD #covid19 resources, APIs, wrapper, endpoints etc.

Good compiled thoughts on Open Source projects:
https://github.com/br-data/open-source-guidelines


## WDR 

- https://github.com/wdr-data/covid19_nrw
  - Mags-Zahlen für NRW https://www.mags.nrw/coronavirus-fallzahlen-nrw
  - RKI-Zahlen von Website: https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/Fallzahlen.html

- https://github.com/ard-data/covid-19
  - John-Hopkins-Zahlen aus diesem Repo: https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports
 
 
  ## HR
  
https://github.com/untergeekDE/scrape-covid19

Enthält: 
- R-Scraper für die HMSI-Zahlen für Hessen (s.u.)
- R-Skript/Scraper zur Abfrage der Daten des DIVI-Intensivbettenregisters
- R-Skript für Daten des RKI; Auswertungen Genesene/Aktive Fälle; Auswertung nach Alterskohorte und Geschlecht
- R-Skript für den [regionalen R-Reproduktionswert-Index des Helmholtz-Instituts](https://gitlab.com/simm/covid19/secir/-/tree/master/img/dynamic/Rt_rawData)

### Endpunkte 

Die Daten werden in der Regel in ein Google Sheet geschrieben.

- Fälle, Inzidenz und Dynamik nach Kreisen https://docs.google.com/spreadsheets/d/1h0bvmSjSC-7osQpt94iGre9K5o_Atfj0UnLyQbuN9l4/edit#gid=0
- Fälle, Todesfälle, Genesene, Wachstumsraten in den letzten vier Wochen https://docs.google.com/spreadsheets/d/1OhMGQJXe2rbKg-kCccVNpAMc3yT2i3ubmCndf-zX0JU/edit#gid=1805279723
- Wachstumsraten und 7-Tage-Trends im Vergleich https://docs.google.com/spreadsheets/d/1NXHj4JXfD_jaf-P3YjA7jv3BYuOwU9_WKoVcDknIG64/edit#gid=1580920358
- Fälle und Todesfälle nach Alter und Geschlecht (RKI-Daten) https://docs.google.com/spreadsheets/d/1RxlykWHoIZEq91M1bJNf26VPn8OWwI6VsgvAO47HM8Q/edit#gid=89632754

Die tägliche Übersicht des Ministeriums wird bis auf weiteres auch hier angeboten: https://d.data.gcp.cloud.hr.de/scrape-hsm.csv
  
### Mangelnde Zuverlässigkeit der Ministeriumsdaten für Hessen

Die Zahlen des Hessischen Ministeriums für Soziales und Integration (HMSI) liegen nur als PDF-Mailing oder [als Tabelle auf einer täglich aktualisierten Seite](https://soziales.hessen.de/gesundheit/infektionsschutz/corona-hessen/taegliche-uebersicht-der-bestaetigten-sars-cov-2-faelle-hessen) vor - die wegen kleiner menschlicher Fehler nicht zuverlässig automatisch gelesen kann. Eine Umstellung auf die RKI-Daten ist deshalb angezeigt. 
