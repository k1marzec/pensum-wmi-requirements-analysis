# Pensum WMI – Analiza Wymagań i Modelowanie Procesów

### Projekt inżynierski | Rola: Business & Systems Analyst
System webowy do automatyzacji i zarządzania rocznym wymiarem godzin dydaktycznych (pensum) pracowników Wydziału Matematyki i Informatyki Uniwersytetu im. Adama Mickiewicza w Poznaniu.

---

##  O projekcie
Głównym celem projektu było całkowite zastąpienie dotychczasowego, rozproszonego i podatnego na błędy procesu opartego na arkuszach kalkulacyjnych Excel oraz wiadomościach e-mail. System centralizuje dane o pracownikach, przedmiotach i grupach, automatyzując wyliczanie obciążeń i nadgodzin w oparciu o regulaminy uczelni.

System został zaprojektowany z myślą o pięciu grupach użytkowników: Kierownikach kierunków, Planistach, Biurze Obsługi Wydziału (BOW), Administratorach (LWiRA) oraz Pracownikach dydaktycznych.

---

##  Moja rola i odpowiedzialność
Jako **Business & Systems Analyst** odpowiadałam za pełen cykl inżynierii wymagań, analizę systemowo-biznesową oraz weryfikację jakościową (QA), łącząc świat biznesowy (administracja wydziału) z technicznym (zespół deweloperski). Uczestniczyłam również w pracach implementacyjnych (full-stack).

### Kluczowe zadania i artefakty (Deliverables):
* **Inżynieria wymagań:** Przeprowadzenie wywiadów eksploracyjnych i ustrukturyzowanych z interesariuszami; identyfikacja 5 głównych problemów biznesowych (P1–P5, m.in. brak kontroli wersji, błędy walidacji)[cite: 1].
* **Modelowanie procesów:** Mapowanie procesów biznesowych i analiza wąskich gardeł w notacji **BPMN 2.0 (modele stanu obecnego AS-IS)**[cite: 1].
* **Projektowanie systemowe:** Definiowanie zakresu systemu za pomocą diagramów przypadków użycia (**UML Use Case**) oraz modelowanie struktury danych[cite: 1].
* **Specyfikacja wymagań:** Tworzenie kompletnego Backlogu w postaci **User Stories z precyzyjnymi Kryteriami Akceptacji**; priorytetyzacja wymagań z użyciem techniki **MoSCoW**[cite: 1].
* **Prototypowanie UI/UX:** Tworzenie iteracyjnych, interaktywnych makiet w systemie **Figma** oraz przeprowadzenie dwóch rund testów użyteczności z użytkownikami[cite: 1].
* **Analiza Integracji:** Specyfikacja modułów integracyjnych: importu strukturyzowanych plików zewnętrznych (**CSV z systemu USOS**) oraz integracji aplikacji z wydziałowym **serwerem pocztowym (SMTP)** do dystrybucji raportów PDF[cite: 1].
* **Weryfikacja wydajności (QA):** Zaprojektowanie i przeprowadzenie technicznych testów obciążeniowych warstwy serwerowej za pomocą narzędzia **Locust**[cite: 1].
* **Zarządzanie projektem:** Koordynacja prac w systemie **JIRA (Tablica Kanban)**; zarządzanie zwinny cyklem życia zadań (*To Do, In Progress, Tests, Bugfixing*)[cite: 1].

---

##  Technologie i narzędzia
* **Analiza, Modelowanie & Projektowanie:** BPMN 2.0, UML, User Stories, MoSCoW, Macierz śledzenia wymagań[cite: 1].
* **Prototypowanie & UX:** Figma[cite: 1].
* **Zarządzanie & Dokumentacja:** Jira, Kanban, Git, Markdown, LaTeX[cite: 1].
* **Testowanie wydajnościowe:** Locust[cite: 1].
* **Development (Aplikacja MVP):** Python (Django), Docker, PostgreSQL, HTML5, CSS3, REST API[cite: 1].

---

##  Struktura repozytorium
* `/documentation` – Pełny dokument wymagań projektowych (SRS), zawierający historię wersji, specyfikację User Stories oraz kryteria akceptacji[cite: 1].
* `/diagrams` – Graficzne modele procesów biznesowych w notacji BPMN 2.0 (proces AS-IS) oraz diagramy przypadków użycia UML[cite: 1].
* `/prototypes` – Ewolucja interfejsu użytkownika (makiety Figma oraz zrzuty ekranu z finalnego, działającego systemu)[cite: 1].
* `/testing` – Wyniki weryfikacji wymagań: macierz śledzenia wymagań funkcjonalnych oraz raporty i wykresy z testów obciążeniowych w narzędziu Locust[cite: 1].

---

##  Kluczowe wnioski z retrospekcji projektu
Projekt inżynierski pozwolił mi na zdobycie praktycznego doświadczenia w zarządzaniu zakresem systemu (Scope Management) w dynamicznym środowisku Agile[cite: 1]. Zderzenie wymagań z ograniczeniami technologicznymi i czasowymi nauczyło mnie:
1. **Zarządzania rozrostem wymagań (Scope Creep):** Wdrożenie twardej zasady "warunku stopu" (późniejsze wymagania nie mogły otrzymać priorytetu Must Have) uchroniło projekt przed paraliżem terminowym[cite: 1].
2. **Wartości wczesnego prototypowania:** Pokazanie klikalnych makiet w Figmie pozwoliło odkryć wymagania ukryte (np. moduł symulacji wariantów obsady), zanim deweloperzy napisali pierwszą linię kodu[cite: 1].
3. **Podejścia Data-Driven do QA:** Weryfikacja systemu za pomocą narzędzia Locust udowodniła stabilność architektury (0% barier błędów i czas odpowiedzi serwera poniżej 40ms dla 10 jednoczesnych użytkowników), co zamknęło techniczne wymagania niefunkcjonalne systemu[cite: 1].

---
*Status projektu: System został doprowadzony do pełnej gotowości wdrożeniowej (MVP spełniające 100% wymagań Must i Should) i przekazany kolejnemu zespołowi do utrzymania i dalszego rozwoju[cite: 1].*
