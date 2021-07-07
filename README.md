# Data-management
Data Management project at University of Milano Bicocca-Data Science.

Il lavoro è consistito nel capire se i tweet pubblicati riferiti ad
una particolare azienda influenzano l’andamento in borsa dell’azienda.
Per rispondere a questa domanda ci siamo interessati a tre diverse
aziende farmaceutiche che hanno pordotto vacini contro il COVID19:
Sinopharm, AstraZeneca, Pfizer. Sono quindi stati estratti i tweet
contenenti il nome di almeno una delle tre aziende integrandoli con i
dati azionario. Le visualizzazioni ci hanno consentito di rappresentare
gli andamenti giornalieri e orari del numero di tweet e degli andamenti
in borsa, includendo anche ulteriori parametri quali la sentiment e gli
engagement dei tweet. Le infografiche non ci hanno consentito di dare
un giudizio chiaro per quanto riguarda un possibile nesso tra i due
andamenti. Il software utilizzato per la parte di integrazione dei dati
è Python Notebook. Per le visualizzazioni grafiche è stato utilizzato
Tableau.

## Dati
Nella cartella Dati si trovano i dati relativi alle azioni, ai tweets e i dataset integrati.


## Codice
Nella cartella codice si trovano due cartelle:
La prima chiamata Data gathering contiene i notebook python relativi alla raccolta dati: 
* 1.A-Snscraper: con cui si effettuata la raccolta dei tweet;
* 1.B-Data stock: con cui si effettuata la raccolta dei dati delle azioni;
* 2.A-Data merge stock: con cui si sono uniti i dataset relativi alle azioni;
* 3.A-Integration_Sinopharm: integrazione di tweet e azioni di Sinopharm;
* 3.B-Integration_Astrazeneca: integrazione di tweet e azioni di Astrazeneca;
* 3.C-Integration_Pfizer: integrazione di tweet e azioni di Pfizer;

Nella cartella Real-time si trovano:
*  I kafka producer e consumer dei dati finanziari e dei tweet, con il workflow Nifi;
* La cartella integration contiene le integrazioni real-time.


The work consisted in understanding whether the published tweets referring to
a particular company influence the company's stock market performance.
To answer this question we are interested in three different ones
pharmaceutical companies that have produced vaccines against COVID19:
Sinopharm, AstraZeneca, Pfizer. Tweets were then extracted
containing the name of at least one of the three companies integrating them with i
stock data. They allowed us to visualize
daily and hourly trends in the number of tweets and trends
on the stock market, also including additional parameters such as sentiment and
engagement of tweets. Infographics did not allow us to dare
a clear judgment regarding a possible link between the two
trends. The software used for the data integration part
is Python Notebook. For graphic reviews it was used
Table.

## Data
In the Data folder you will find data relating to actions, tweets and integrated datasets.


## Code
There are two folders in the code folder:
The first call Data gathering contains the python notebooks related to data collection:
* 1.A-Snscraper: with which the collection of tweets is carried out;
* 1.B-Data stock: with which the data of the shares is collected;
* 2.A-Data merge stock: with which the datasets relating to the shares are combined;
* 3.A-Integration_Sinopharm: integration of tweets and Sinopharm shares;
* 3.B-Integration_Astrazeneca: integration of tweets and actions of Astrazeneca;
* 3.C-Integration_Pfizer: integration of Pfizer tweets and actions;

In the Real-time folder you will find:
* Kafka producers and consumers of financial data and tweets, with the Nifi workflow;
* The integration folder contains real-time integrations.
