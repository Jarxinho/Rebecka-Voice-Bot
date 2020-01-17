# Rebecka-Voice-Bot

Group Project
PWSZ Nowy Sącz

![ChatBot](https://miro.medium.com/max/1200/0*Ocrf5g0MBNVSOrG1.png)

## 1.	Dla kogo?

Dla restauracji które otrzymują dużo zamówień telefonicznych od swoich klientów


## 2.	Cel = efekt projektu.

Zastąpienie rutynowej czynności wykonywanej przez człowieka VoiceBotem „Rebeka”. Zmniejszenie liczby etatów. Usprawnienie procesu złożenia zamówienia.

## 3.	Termin.

31.12.2019

## 4.	Wsteczna lista kroków koniecznych do realizacji projektu. 

Dane zamówienia oraz klienta zapisują się w bazie danych, stworzenie bazy, geolokalizacja kuriera z zamówieniem, oszacowanie czasu oczekiwania na zamówienie na podstawie capacity restauracji, dnia tygodnia, ułożenie dialogów, nagranie odpowiedzi, integracja z API DialogFlow, Voximplant.
Poproszenie o wystawienie opinii jakości usług Rebeki, określenie czasu oczekiwania na zamówienie, przekazanie danych zamówienia do realizacji, poproszenie o kod rabatowy, zatwierdzenie zamówienia, określenie miejsca dostawy, wybranie dodatków, wybranie produktów, odebranie połączenie od klienta, rozpoczęcie mechanizmu nagrywania rozmów, uruchomienie linii telefonicznej.

## 5.	Analiza

Celem projektu jest stworzenie asystenta głosowego, który będzie potrafił przyjąć zamówienie jedzenia od klienta i odpowiedzieć na podstawowe pytania klienta: 
Przyjęcie zamówienia, Zgłoszenie reklamacji, Lokalizacja zamówienia



![Analysis1](https://imagizer.imageshack.com/img924/1167/LtpT26.png)
Rys. 1.0. Struktura podziału pracy WBS (ang. Work Breakdown Structure) dla projektu Asystent głosowy (uszczegółowiono tylko fazę implementacji)

W tabeli przedstawiono 14 czynników, które szacuje projektant w skali od 1 do 5 jako współczynniki mające istotne znaczenie dla złożoności, wielkości i problemów napotykanych przy budowie oprogramowania.



![Analysis2](https://imagizer.imageshack.com/img923/4290/8Z9bdB.png)

Suma kosztów: 30 pkt 


## 6.  Metodologia

  Metodologia Agile – Manifest Agile
  
  Cechy charakterystyczne Agile:
  
- Ten typ zarządzania projektem kładzie szczególny nacisk na kontakt z klientem oraz drobne zmiany w planie działania, które mają usprawnić pracę i zapewnić lepszy finalny produkt.
- Zespoły pracujące wg metody Agile skupiają się na szybkim dostarczeniu dobrej jakości wersji produktu, która w kolejnych iteracjach (sprintach) jest ulepszana lub zmieniana zgodnie z aktualnymi wymaganiami klienta.
- Agile opiera się na tzw. sprintach, czyli małych blokach, które obejmują zdefiniowany zakres “rzeczy do zrobienia”.
- Realizacja każdego tego typu elementu, zwanego “feature” przynosi określone pozytywne skutki dla całego projektu.
- Sprinty przydają się szczególnie wtedy, gdy zależy ci na szybkich efektach lub twój projekt przez całą fazę tworzenia ulega zmianom.
- Agile kładzie szczególny nacisk na samodzielność zespołu, który może decydować o przebiegu pracy bez potrzeby uzyskania zgody od kierownictwa.
- Metoda Agile jest użyteczna nie tylko w zarządzaniu IT, ale również w przypadku, gdy w firmie niezbędna jest reorganizacja lub zmiana procesów biznesowych.

 Przy realizacji zadań w projektach w oparciu o metodykę programowania zwinnego wyróżnia się następujące po sobie etapy: 
   
- Planowanie – zbieranie dokładnych wymagań od klienta dotyczących danego zadania, ich analiza oraz zaplanowanie kroków koniecznych do realizacji danego zadania w oparciu o pozyskane informacje. Etap ten wymaga bezpośredniego kontaktu z klientem, a co za tym idzie umiejętności dobrej komunikacji i zrozumienia drugiej osoby. 
   
- Projektowanie – projektowanie wykonania danego elementu będącego celem zadania na bazie informacji zebranych na etapie planowania. Można to porównać do wykonania projektu elementu domu przez architekta przed przystąpieniem do prac nad nim przez ekipę budowlaną. 
    
- Programowanie – właściwy etap prac nad danym zadaniem na bazie przygotowanego projektu zadania. 
    
- Testowanie – testowanie danego elementu będącego podmiotem zadania od strony technicznej przez osobę lub zespół wykonujący dane zadanie oraz od strony klienta czy dany element jest tym czego klient oczekiwał.

- Implementacja – po pozytywnych wynikach testów przekazanie danego elementu projektu na „produkcję” do finalnego użytkowania przez klienta. 
    
- Informacja zwrotna – przekazanie informacji zwrotnej przez klienta do osoby lub zespołu realizującego dane zadanie w projekcie odnośnie ewentualnych mniejszych błędów, których nie wykryto podczas testów, zgłaszanie potencjalnych usprawnień do realizacji w kolejnych cyklach lub zgłoszenie zmiany wymagań klienta. Mając na myśli zmianę wymagań mówimy o rzeczywistej zmianie wymagań - wynikłej np. ze zmiany procesów lub potrzeb klienta - nie natomiast jak zaznaczono wcześniej o zmianie wynikającej z pominięcia lub niedokładnego przeprowadzenia etapu Planowania. 

   Powyższe etapy tworzą cykl powtarzany do czasu zakończenia danego zadania. Bardzo ważne jest zaznaczenie, iż kolejne cykle mają służyć ewentualnemu skorygowaniu przygotowanego zadania na bazie informacji klienta lub elastycznemu wprowadzaniu ewentualnych zmian wymagań ze strony klienta jeżeli takie się pojawiły w formie informacji zwrotnej (feedback). Kolejne cykle nie mają natomiast na celu – jak błędnie przyjmuje część „chaotycznych / niezorganizowanych” osób lub zespołów – nieskończone poprawianie błędów danego zadania wynikających z pominięcia lub niedokładnego przeprowadzenia etapu Planowania w tym zbierania i analizy wymagań od klienta.
   
   Podstawowe zasady
    
- osiągnięcie satysfakcji klienta poprzez szybkość wytwarzania oprogramowania,

- podstawową miarą postępu jest działające oprogramowanie,

- późne zmiany w specyfikacji nie mają destrukcyjnego wpływu na proces wytwarzania oprogramowania,

- bliska, codzienna współpraca pomiędzy biznesem a deweloperem,

- bezpośredni kontakt jako najlepsza forma komunikacji w zespole i poza nim,

- ciągła uwaga nastawiona na aspekty techniczne oraz dobry projekt (design),

- prostota- sztuka maksymalizacji ilości pracy, która nie została wykonana – jest niezbędna

- samoorganizacja zespołów,

- regularna adaptacja do zmieniających się wymagań.

   Częstym błędem występującym u osób i zespołów stosujących metodykę agile jest nadinterpretacja jej założeń i całkowicie błędne pomijanie bardzo ważnych etapów projektu tj. fazy zbierania wymagań, a następnie na ich podstawie faz analizy oraz planowania.
   
   

## 7.	Lista zadań
    
    SHOR-TERM
    
   - [Scenariusze rozmów ( 2 dni) DW](https://github.com/Jarxinho/Rebecka-Voice-Bot/blob/develop/Rebeka%20scenariusz%20voicebot.pdf)
    
   - [Zaprojektowanie bazy danych, wybranie technologii, tabele, kolumny, relacje (3dni) JP](https://github.com/Jarxinho/Rebecka-Voice-Bot/blob/develop/images/voicebot.png)
    
   - [Stworzenie dokumentacji projektu ( 3 dni) DW](https://github.com/Jarxinho/Rebecka-Voice-Bot/blob/develop/Dokumentacja%20techniczna.pdf)
    
   - Stworzenie repo w GIT i opublikowanie projektu oraz dokumentacji( 1 dzien) JS
    
   - [Analiza rynku, jakie są dostępne API ChatBot/VoiceBot, porównanie ( 2 dni) JS](https://github.com/Jarxinho/Rebecka-Voice-Bot/blob/develop/docs/shor_term/Bots_Comparison.xlsx)
    
   - Analiza planu B ( 2 dni) . JS
    
   - Analiza porównanie dostępnych rozwiązań monitoringu aplikacji ( 5 dni). KP
    
   - Wybór Metodologii (2dni) MS
    
   - [Analiza ryzyka, uporządkowanie repozytorium (3 dni ) MS](https://github.com/Jarxinho/Rebecka-Voice-Bot/blob/develop/AnalizaRyzyka.md)
    
   - [Diagram przypadków użycia (3 dni) DW](https://github.com/Jarxinho/Rebecka-Voice-Bot/blob/develop/Diagram%20przypadkow%20uzycia.pdf)
    
   - Wybór najlepszego rozwiązania monitoringu, obszar testów (3 dni) KP
    
   - Połączenie DialogFlow z MySQL na podstawie innej prostej aplikacji (3dni) JP
   
    LONG-TERM
   
   - Implementacja dialogflow (30dni) JS
   
   - Udostępnienie aplikacji na świat, wybór dostawcy hostingu ( po skończeniu implementacji) (2dni)
   
   - Implementacja monitoringu, healtchecki, alerty .
   

## 8.	Plan B

  Analiza planu B
  ![Alternatives](https://static.adweek.com/adweek.com-prod/wp-content/uploads/2018/04/marketing-alternatives-content-2018.jpg)
  
  *Po przeanalizowaniu rynku i dostępnych na nim rozwiązań Voicebot/Chatbot service za cel obraliśmy implementację VoiceBota na platformie Dialogflow.
Z analizy wynika, że platforma najlepiej sprawdzi się w projekcie. 
Absolutnym must have przy podjęciu tej decyzji było wsparcie języka polskiego, gdyż produkt jest przeznaczony na polski rynek, polskojęzycznych klientów. 
To kryterium na dzień dzisiejszy spełniają jedynie dwa rozwiązania: Dialogflow oraz Wit.ai. Jednakże Dialogflow ma zdecydowanie więcej funkcjonalności, które mogą okazać się przydatne w projekcie. 
Ponadto licencja freemium w przypadku tego projektu będzie wystarczająca. 
Możliwość licznych integracji z zewnętrznymi aplikacjami/komunikatorami takimi jak: Google Assistant, Messenger, Slack, Twitter jest niezwykle cenna w przypadku realizowanego projektu gdyż w/w aplikacje na dobre zadomowiły się w życie Polaków, łatwiej będzie zachęcić potencjalnych klientów do skorzystania z już wcześniej znanego komunikatora.
Gdyby realizacja projektu za pomocą Dialogflow okazała się barierą nie do przeskoczenia, alternatywą pozostaje wit.ai, który oferuje wsparcie języka polskiego.*

Po przeanalizowaniu ryzyka i ścieżki krytycznej wdrożenia Voice Bota jego złożoności i trudności w implementacji.
Konieczności integracji NLP, NLU, NLG, ERM.
Potrzebnej infrastruktury do realizacji połączeń, nagrywania i przetwarzania intencji do restauracji.
Mając na względzie deadline 31.12.2019. 
Podjęliśmy decyzje z zespołem, że jeśli do 5 grudnia nie uda się zrealizować kamieni milowych w projekcie Voice Bot Rebeka, wówczas podejmiemy rękawice wdrożenia Chat Bot, który jest mniej złożony. 


## 9.	Monitoring i testowanie

### Elasticsearch
Elasticsearch to rozproszony silnik wyszukiwania oparty o Apache Lucene. Elasticsearch to tak naprawdę niezależna baza danych, stworzona w Javie. Rozproszony dlatego ponieważ umożliwia klastrowanie czyli uruchomienie wielu instancji tej samej aplikacji tworzącą jedną, dzięki czemu możemy stworzyć naprawdę dużą i wydajną bazę danych, która przyjmie dane wsadowe w wielu zaawansowanych formatach, a co najważniejsze umożliwi szybkie wyszukiwanie pełnotekstowe, a na dodatek będzie łatwa w obsłudze dla deweloperów, ponieważ komunikacja z Elasticsearch następuje za pomocą JSON. Technicznie rzecz ujmując, Elasticsearch jest niezwykłą bazą danych. Na jego wyjątkowość wpływa kilka czynników: • dane przechowywane są w tzw. indeksach, czyli zbiorach dokumentów (całość oparta jest na bibliotece Lucene), • dane można wydobywać za pomocą zapytań Elasticsearch DSL wysyłanych za pomocą REST API, • jest systemem rozproszonym i bardzo dobrze skaluje się horyzontalnie – możemy dokładać kolejne node’y, zaś Elasticsearch zajmie się resztą (np. odpowiednim rozszerzeniem klastra i podziałem danych pomiędzy serwery) i przyspieszy działanie.

### Icinga 
Icinga to narzędzie aktywnie monitorujące podzespoły danego systemu. W klasycznym podejściu, gdzie aplikacje, bazy i inne komponenty aplikacji webowej są umieszczone na serwerach, mogą być one monitorowane przez
agenta NRPE. Serwer Icinga przesyła do nich zapytania o konkretne czujki i metryki sprawdzające np. obciążenie procesora, ilość dostępnej pamięci dyskowej, długość kolejek, czas ładowania strony czy ilość zapytań do bazy danych. W zależności od ustawień Icingi, możemy zdefiniować zadania jakie mają zostać wykonane w przypadku wystąpienia sytuacji krytycznej: od powiadomienia odpowiednich osób po wykonanie automatycznej akcji.

### Grafana 
Grafana to narzędzie bardziej rozbudowane graficznie, jednak gorsze pod kątem powiadomień niż Icinga. Narzędzie to pozwala na wizualizacje danych w postaci wykresów, wskaźników, diagramów obrazujących kluczowe metryki działania aplikacji. Źródłem danych do Grafany może być baza danych ElasticSearch, InfluxDB, SQL czy AWS CloudWatch. Dobrze skonstruowany dashboard pozwala określić obecny oraz historyczny stan całego środowiska. Wykresy mogą być uzupełniane odpowiednimi adnotacjami, takimi jak uruchomienie nowszej wersji aplikacji, co pozwala na łatwe odnajdywanie zależności pomiędzy wydajnością środowiska, a wersją aplikacji. Grafana nadaje się również do tworzenia wizualizacji metryk sprawdzanych rutynowo, pozwalając sprawnemu administratorowi na przewidzenie awarii – np. kończącej się pamięci czy przestrzeni dyskowej – przed ich wystąpieniem. Grafana, umożliwia także definiowanie prostych reguły powiadomień, choć znacznie bardziej ubogich niż Icinga.

### Kibana 
Kibana jest narzędziem służącym do eksploracji zbiorów danych, które umożliwia agregację logów z różnych źródeł. Poza funkcjami takimi jak przeglądanie i sprawne przeszukiwanie logów, pozwala tworzyć widoki z wykresami, a także posiada moduł timelion, pozwalający na analizę trendów czy analizę danych w czasie. Poza tworzeniem wykresów i składaniem z nich dashboardów, można skonstruować zapytanie timelion, które będzie wyszukiwało anomalie między danymi, na przykład tydzień do tygodnia. Bazą danych dla Kibany jest zazwyczaj indeks ElasticSearch, który może być użyty również przez wspomnianą wcześniej Grafanę. Oba te narzędzia dają w połączeniu świetny zestaw do przeglądania i wizualizacji zbieranych metryk.

### Prometheus
Prometeus jest bardzo dobrym narzędziem dedykowanym nowoczesnym środowiskom: automatycznie skalowanych, dynamicznych, konteneryzowanych, o niedeterministycznym czasie życia komponentów. W relatywnie prosty sposób, można dokonać integracji z katalogiem usług wystawionych przez service discovery (np. consul, eureka). Za pomocą Prometheusa umożliwione jest także zbieranie danych, używając protokołu http(s) z wykorzystaniem rozmaitych exporterów. Prometheus integruje się z Grafaną, posługując się nią jako silnikiem do wizualizacji danych oraz z alert managerem, jako modułem do agregacji alarmów i wysyłania powiadomień.

### Graylog
Graylog to opensourcowy projekt, który jest rozwijany od 2009 roku. Jego twórcy od samego początku chcieli stworzyć system do analizy logów pochodzących z przeróżnych źródeł: systemów operacyjnych, serwerów aplikacji, firewalli sprzętowych i programowych. Dzięki temu Graylog znajduje zastosowanie zarówno podczas monitoringu stron internetowych, aplikacji webowych i wielu obszarów infrastruktury informatycznej. Jego użytkownikami mogą być nie tylko pracownicy zespołów IT, ale również działy sprzedaży i marketingu, zainteresowane m.in. wizualizacją trendów. Graylog przetwarza logi pochodzące z wielu różnych źródeł. Podstawowym warunkiem jest jednak zgodność plików dzienników zdarzeń z powszechnie stosowanym standardem opisanym w dokumentach RFC 5424 i 3164, które definiują m.in. takie reguły jak sposób zapisu daty i nazwy hosta źródłowego. Obsługiwane są logi pochodzące z serwerów Linux/Unix, wysyłane za pomocą protokołów TCP i UDP przez serwisy syslog oraz syslog-ng. Konfiguracja tych klientów nie odbiega zbytnio od standardowej, definiującej przesyłanie logów do centralnego serwera stworzonego za pomocą wspomnianych serwisów.

![Monitoring](https://github.com/Jarxinho/Rebecka-Voice-Bot/blob/develop/images/compare.PNG)
