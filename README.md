# Roadmap of wapka project

poniżej kilka  informacji o idei, twórcy i planów.

## Rozwiązanie na dekady

Dla jednych drzwi do internetu otwierają wyszukiwarki, dla innych media społecznościowe. 
W dobie IoT nie potrzebujemy ekranu i klawiatury, możemy po prostu mówić, rozmawiać jak z człowiekem.
Technologie bazujące na sztucznej inteligencji pozwalają pominąć bezpośrednią interakcję na rzecz obserwacji i analizy zachowania.
Komunikacja bez słów i gestów a jedynie wyciąganiu wniosków i reagowaniu stosownie do sytuacji i potrzeb użytkownika.

## Tom Sapletta, Software Deveoper

Jako Software Deveoper z ponad 10 letnim stażem pracuję nad rozwiązaniami do optymalizacji procesu prototypowania.
Doświadczenie podczas refaktoryzacji dały mi odpowiedź na to co najczęściej podelga zmianom i jak przygotwać kod aplikacji, aby nie był przemdiotem częstych zmian. Na co dzień pracuję przy projektach jako DevOps oraz przeprowadzam prace badawcze w firmie Softreck nad efektywniejszym prototypowaniem aplikacji


## [Softreck - Leadership Through Software Development](https://softreck.pl/)

W firmie Softreck budujemy rozwiązania na przyszłe dekady, dołącz do nas jako #programista, #inwestor, #ambasador
Obecnie rozwijamy otwarty projekt Web Stream Dev do streamowania aplikacji przez www, w drodze są przygotowania do komercjalizacji prototypowania One Day Run


# Idea Webstream

## Pryncypia stojące za powstaniem Webstream

Droga do uzyskania najlepszy efekt zaangażowanej energii i czasu do reużycia kodu.
Wnioski są następujące:

1. Hipermodularyzacja, czyli używanie jak najmniejszych modułów kodu, ściśle dla określonego środowiska w natywnym jezyku
2. Definiowanie pojedynczych funkcji jako pojedynczego projektu w celu pozbycia się zależności od innych bibliotek
3. Nie używanie frameworków i abstrakcji wprowadzających większą złożoność i wpływającą negatywnie na krzywą uczenia się
4. Budowanie kodu na podstawie jak największej ilości już zdefiniowanej logiki, wkorzystanie już istniejących usług dostępnych przez np RestAPI
5. Wykorzystanie dowolnej technologii dla której można zaoferować środowisko uruchomieniowe, zamiast tworzenia nowego rozwiązania w znanym języku programowania

Te pryncypia są stosowane przy użyciu biblioteki WebStream oraz całego ekosystemu [wapka.pl](https://docs.wapka.pl/))
W chwili obecnej kod jest ładowany w formie drzewa JSON z listą mediów jakie mają być załadowane
więcej informacji tutaj:
[docs.webstream.dev](https://docs.webstream.dev/#/)



# Ekosystem Wapka

![logo wapka.pl](https://logo.wapka.pl/3/cover.png)


### Co to jest?

The Wapka is an OpenSource Deployment Ecosystem to meet both:

This is win-win ecosystem: Programmer and Non-technical people have an opportunity to make a working business with our support on background


## Do czego służy?

Ekosystem technologiczny dla otwartego oprogramowania do uruchamiania aplikacji z otwartym kodem OpenSource na dowolnym serwerze/infrastrukturze


### Dla kogo?

Ekosystem dla 2 grup użytkowników:
+ programistów chcących udostępnić swój projekt do szerszego wykorzystania w jak najkrótszym czasie (MVP)
+ użytkowników chcących używać otwartego oprogramowania bez udziału programistów czy adminstartorów a jednoczenie:
+ mieć dostep online do obsługi technicznej w celu ułatwienia korzystania z ekosystemu jak i przy rozwiązywaniu codziennych problemów

Szukających rozwiązania dla narzędzi tymczasowych, które chcieliby używać bez udziału programistów
Ekosystem dla programistów szukających rozwiązania dla ich deploymentu


## Rozwiązania

Całość rozwiązań, ekosystem w roboczej nazwie wapka (web-aplikacja), oferta, informace, aktualizacje, szkolenia

[Roadmap of wapka project - roadmap.wapka.pl](https://roadmap.wapka.pl/)

*nazwa globalna: https://roadmap.modula.dev

Rozwiązania są skierowane na zwiększenie efektywności wszystkich klientów działajacych na rzecz:
+ definiowania rozwiązania poprzez zrozumienie problemów i idei
+ wdrażania projektów poprzez zapewnienie odpowiednio wykwalifikowanej kadry
+ automatyzacji utrzymania poprzez najlepsze narzędzia
+ uniezależniania się od stron trzecich udostępniających cały ekosystem, bez możliwości wyboru, zmiany, migracji
+ Rozwiazanie wapka, zmodularyzowane elementy, które pozostają fizycznie niezaleznie, daje to szansę szybszego rozwoju niż w przypadku monolitycznych scalonych rozwiązaniach zatracające cechy elastyczności.




### Biblioteka

Biblioteka do hipermodularyzacji stron/aplikacji www

[roadmap.webstream.dev](https://roadmap.webstream.dev/#/)

### Pluginy 
rozszerzenia do biblioteki na przeglądarke, wordpress


### Providerzy

Partnerzy oferujący usługi wynajmu infrastruktury+
+ hosting
+ vps
+ cloud


### Marketplace

Marketplace z gotowcami bazujące na bibliotece webstream, wersja SaaS eksperymentalna polska

[roadmap.application.pl](https://roadmap.application.pl/#/)

*wersja globalna: https://roadmap.mvps.dev/


### SaaS - software house
4. Usługa SaaS dla Software House, wersja globalna

[roadmap.oneday.run](https://roadmap.oneday.run/#/)



### SaaS - dla każdego
5. Usługa SaaS dla Kowalskich, wersja SaaS eksperymentalna polska

[roadmap.prototypowanie.pl](https://roadmap.prototypowanie.pl/#/)

*wersja globalna: https://roadmap.webapks.com/


## Kolejne projekty jak zostaną zrealziowane powyższe


Za pomocą usłgui deployment.pl możliwy jest szybki cykl uruchomienia i monitorowania aplikacji oparty o małe VPS, zarządzane przez ProMaGen.com
Plan na początek to infratstruktura z kilkudziesięcioma serwerami z dostępem przez oAuth/... dla użytkowników z subscription.pl


## Ułatwienia integracji poprzez prostą autoryzację

+ www: subscription.pl
  + oferta
  + integracja oferty z ofertą/rozwiązaniami partnerów
  + server: vps z foundation


## Etapy

w pierwszym etapie 

+ www: wapka.pl
  + blog informacyjny
  + plan, roadmap
  + zespół

## TODO:

+ blog about news in our ecosystem
+ newsletter to know about news on application directory
+ integration with foundation
+ program partnerski dla programistów, aby im się opłacało używać to rozwiązanie
+ program partnerski dla aktualnych klientów subscription.pl




  
+ www: application.pl
  + lista aplikacji dodanych poprzez deployment
  + możliwości kliknięcia deployment
  


## [wapka.pl page](https://www.wapka.pl/)
+ [logo wapka.pl page](https://logo.wapka.pl/)
+ [docs wapka.pl page](https://docs.wapka.pl/)
+ [roadmap wapka.pl page](https://roadmap.wapka.pl/)

+ [Oferta, Model Biznesowy](https://roadmap.wapka.pl/)
+ [Technologie, Ekosystem](https://docs.wapka.pl/EKOSYSTEM.html)

## Softreck's OpenSource Deployment Ecosystem
+ [Softreck - Leadership Through Software Development](https://softreck.pl/)
+ [culture.softreck.dev](https://culture.softreck.dev/#/)
+ [Softreck’s OpenSource Deployment Ecosystem](https://docs.wapka.pl/)
+ [Softreck - Leadership Through Software Development](https://softreck.com/)
+ [Welcome to Portfolio of Softreck Company - softreck.dev](https://softreck.dev/)



---
+ [edit](https://github.com/wapka-pl/roadmap/edit/main/README.md)

```
https://github.com/wapka-pl/roadmap.git
```
