# Rebecka-Voice-Bot

Group Project
PWSZ Nowy Sącz

![ChatBot](https://miro.medium.com/max/1200/0*Ocrf5g0MBNVSOrG1.png)

1.	Dla kogo? Dla restauracji które otrzymują dużo zamówień telefonicznych od swoich klientów
2.	Cel = efekt projektu. Zastąpienie rutynowej czynności wykonywanej przez człowieka VoiceBotem „Rebeka”. Zmniejszenie liczby etatów. Usprawnienie procesu złożenia zamówienia.
3.	Termin. 31.12.2019
4.	Wsteczna lista kroków koniecznych do realizacji projektu. 
Dane zamówienia, klienta zapisują się w bazie danych, stworzenie bazy, geolokalizacja kuriera z zamówieniem, oszacowanie czasu oczekiwania na zamówienia na podstawie capacity, dnia tygodnia, ułożenie dialogów, nagranie odpowiedzi, integracja z API Twilio/Watson.
Poproszenie o wystawienie opinii jakości usług Rebeki, określenie czasu oczekiwania na zamówienie, przekazanie danych zamówienia do realizacji, poproszenie o kod rabatowy, zatwierdzenie zamówienia, określenie miejsca dostawy, wybranie dodatków, wybranie produktów, odebranie połączenie od klienta, rozpoczęcie mechanizmu nagrywania rozmów, uruchomienie linii telefonicznej.
5.	Analiza
Celem projektu jest stworzenie asystenta głosowego, który będzie potrafił przyjąć zamówienie jedzenia od klienta i odpowiedzieć na podstawowe pytania klienta: 
Przyjęcie zamówienia, Zgłoszenie reklamacji, Lokalizacja zamówienia
Rys. 1.0. Struktura podziału pracy(WBS) dla projektu Asystent głosowy (uszczegółowiono tylko fazę implementacji)

![Analysis1](https://imagizer.imageshack.com/img924/1167/LtpT26.png)
W tabeli przedstawiono 14 czynników, które szacuje projektant w skali od 1 do 5 jako współczynniki mające istotne znaczenie dla złożoności, wielkości i problemów napotykanych przy budowie oprogramowania.

![Analysis2](https://imagizer.imageshack.com/img923/4290/8Z9bdB.png)

Suma kosztów: 30 pkt

6.  Metodologia #in progress - 

  Metodologia Agile – Manifest Agile
Cechy charakterystyczne Agile:
Ten typ zarządzania projektem kładzie szczególny nacisk na kontakt z klientem oraz drobne zmiany w planie działania, które mają usprawnić pracę i zapewnić lepszy finalny produkt.
Zespoły pracujące wg metody Agile skupiają się na szybkim dostarczeniu dobrej jakości wersji produktu, która w kolejnych iteracjach (sprintach) jest ulepszana lub zmieniana zgodnie z aktualnymi wymaganiami klienta.
Agile opiera się na tzw. sprintach, czyli małych blokach, które obejmują zdefiniowany zakres “rzeczy do zrobienia”.
Realizacja każdego tego typu elementu, zwanego “feature” przynosi określone pozytywne skutki dla całego projektu.
Sprinty przydają się szczególnie wtedy, gdy zależy ci na szybkich efektach lub twój projekt przez całą fazę tworzenia ulega zmianom.
Agile kładzie szczególny nacisk na samodzielność zespołu, który może decydować o przebiegu pracy bez potrzeby uzyskania zgody od kierownictwa.
Metoda Agile jest użyteczna nie tylko w zarządzaniu IT, ale również w przypadku, gdy w firmie niezbędna jest reorganizacja lub zmiana procesów biznesowych.

    Przy realizacji zadań w projektach w oparciu o metodykę programowania zwinnego wyróżnia się następujące po sobie etapy: 
   Planowanie – zbieranie dokładnych wymagań od klienta dotyczących danego zadania, ich analiza oraz zaplanowanie kroków koniecznych do realizacji danego zadania w oparciu o pozyskane informacje. Etap ten wymaga bezpośredniego kontaktu z klientem, a co za tym idzie umiejętności dobrej komunikacji i zrozumienia drugiej osoby. 
   
Projektowanie – projektowanie wykonania danego elementu będącego celem zadania na bazie informacji zebranych na etapie planowania. Można to porównać do wykonania projektu elementu domu przez architekta przed przystąpieniem do prac nad nim przez ekipę budowlaną. 
    
Programowanie – właściwy etap prac nad danym zadaniem na bazie przygotowanego projektu zadania. 
    
Testowanie – testowanie danego elementu będącego podmiotem zadania od strony technicznej przez osobę lub zespół wykonujący dane zadanie oraz od strony klienta czy dany element jest tym czego klient oczekiwał.

Implementacja – po pozytywnych wynikach testów przekazanie danego elementu projektu na „produkcję” do finalnego użytkowania przez klienta. 
    
Informacja zwrotna – przekazanie informacji zwrotnej przez klienta do osoby lub zespołu realizującego dane zadanie w projekcie odnośnie ewentualnych mniejszych błędów, których nie wykryto podczas testów, zgłaszanie potencjalnych usprawnień do realizacji w kolejnych cyklach lub zgłoszenie zmiany wymagań klienta. Mając na myśli zmianę wymagań mówimy o rzeczywistej zmianie wymagań - wynikłej np. ze zmiany procesów lub potrzeb klienta - nie natomiast jak zaznaczono wcześniej o zmianie wynikającej z pominięcia lub niedokładnego przeprowadzenia etapu Planowania. 

   Powyższe etapy tworzą cykl powtarzany do czasu zakończenia danego zadania. Bardzo ważne jest zaznaczenie, iż kolejne cykle mają służyć ewentualnemu skorygowaniu przygotowanego zadania na bazie informacji klienta lub elastycznemu wprowadzaniu ewentualnych zmian wymagań ze strony klienta jeżeli takie się pojawiły w formie informacji zwrotnej (feedback). Kolejne cykle nie mają natomiast na celu – jak błędnie przyjmuje część „chaotycznych / niezorganizowanych” osób lub zespołów – nieskończone poprawianie błędów danego zadania wynikających z pominięcia lub niedokładnego przeprowadzenia etapu Planowania w tym zbierania i analizy wymagań od klienta.
    Podstawowe zasady
    •	osiągnięcie satysfakcji klienta poprzez szybkość wytwarzania oprogramowania,
    •	podstawową miarą postępu jest działające oprogramowanie,
    •	późne zmiany w specyfikacji nie mają destrukcyjnego wpływu na proces wytwarzania oprogramowania,
    •	bliska, codzienna współpraca pomiędzy biznesem a deweloperem,
    •	bezpośredni kontakt jako najlepsza forma komunikacji w zespole i poza nim,
    •	ciągła uwaga nastawiona na aspekty techniczne oraz dobry projekt (design),
    •	prostota- sztuka maksymalizacji ilości pracy, która nie została wykonana – jest niezbędna
    •	samoorganizacja zespołów,
    •	regularna adaptacja do zmieniających się wymagań.

   Częstym błędem występującym u osób i zespołów stosujących metodykę agile jest nadinterpretacja jej założeń i całkowicie błędne pomijanie bardzo ważnych etapów projektu tj. fazy zbierania wymagań, a następnie na ich podstawie faz analizy oraz planowania.

7.	[Lista zadań](Scheme.md)

8.	[Plan B](/images/PlanB.MD)
9.	Monitoring i testowanie #in progress

