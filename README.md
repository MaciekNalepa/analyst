# Analyst-portfolio

[Wersja polska](#wersja-polska)

**Business Analysis – BPMN and UML Modeling**

This project demonstrates business process modeling skills using BPMN 2.0 notation in a real-world sports competition scenario. The model describes the complete start procedure of a diver during a national diving competition — from the moment the athlete receives information about the scheduled dive to the assignment of judges’ scores.

**Project Goal**

The purpose of this project is:
to demonstrate BPMN 2.0 modeling skills, including process structure, decision logic, and exception handling
to develop an understanding of how a real-world operational process works in practice
to provide a foundation for future system design work, where the business process is translated into system architecture (UML-based analysis and design)

**Process Description**

The process begins when the athlete receives information about the scheduled dive.
Before the dive can be performed, the announced dive data must be verified. If any inconsistencies are detected, a correction request is issued, and the athlete may either provide corrected information or withdraw from the attempt.
Once the announcement is accepted, the athlete takes the starting position and waits for the chief judge’s signal. After receiving the signal, the dive is executed and then validated according to competition rules.
Depending on the outcome of the validation, the dive is either scored by the judges or assigned a score of zero in the case of an invalid attempt.

**Key BPMN Elements**

- Exclusive Gateways (XOR)
- Message Events
- Intermediate Events
- Error Handling Paths
- Alternative Process Flows
- Start and End Events

**The model covers**

- dive announcement verification
- correction handling
- athlete withdrawal scenarios
- athlete preparation for the dive
- start authorization by the chief judge
- dive execution
- dive validation
- judges’ score assignment / zero score assignment
- process completion

**Future Development**

This BPMN model represents the business-process layer of a larger analytical and system design initiative.
The next stage will focus on UML-based modeling of the supporting information system, including components responsible for:

- collecting judges’ scores
- validating scoring data
- calculating final results
- managing competition rankings
- storing competition data

The BPMN model describes the business reality of the process, while the UML models will describe the information system required to support and operate it.<br><br>


***

*##Wersja polska*

Analiza biznesowa – modelowanie BPMN i UML

Ten projekt prezentuje umiejętności modelowania procesów biznesowych z wykorzystaniem notacji BPMN 2.0 w rzeczywistym scenariuszu zawodów sportowych. Model opisuje kompletną procedurę startu zawodnika podczas krajowych zawodów w skokach do wody — od momentu otrzymania informacji o zaplanowanym skoku aż do przypisania ocen sędziowskich.

**Cel projektu**

Demonstracja umiejętności modelowania w BPMN 2.0, obejmujących strukturę procesu, logikę decyzyjną oraz obsługę wyjątków
rozwinięcie zrozumienia, jak w praktyce działa rzeczywisty proces operacyjny
stworzenie fundamentu pod przyszłe prace projektowe w zakresie projektowania systemów, gdzie proces biznesowy jest przekształcany w architekturę systemu (analiza i projektowanie w UML)

**Opis procesu**

Proces rozpoczyna się w momencie, gdy zawodnik otrzymuje informację o zaplanowanym skoku. Przed wykonaniem skoku dane dotyczące zgłoszenia muszą zostać zweryfikowane. W przypadku wykrycia niezgodności zgłaszana jest prośba o korektę, a zawodnik może przekazać poprawione dane albo wycofać się z próby. Po zaakceptowaniu zgłoszenia zawodnik zajmuje pozycję startową i oczekuje na sygnał sędziego głównego. Po jego otrzymaniu skok zostaje wykonany, a następnie zweryfikowany zgodnie z zasadami zawodów. W zależności od wyniku weryfikacji skok jest oceniany przez sędziów lub otrzymuje ocenę zero w przypadku próby uznanej za nieważną.

**Kluczowe elementy BPMN**

- Bramki wyłączne (XOR)
- Zdarzenia komunikacyjne (Message Events)
- Zdarzenia pośrednie (Intermediate Events)
- Ścieżki obsługi błędów
- Alternatywne przepływy procesu
- Zdarzenia startowe i końcowe
- Zakres modelu

**Model obejmuje**

- weryfikację zgłoszenia skoku
- obsługę korekt zgłoszenia
- scenariusze wycofania zawodnika
- przygotowanie zawodnika do skoku
- autoryzację startu przez sędziego głównego
- wykonanie skoku
- weryfikację skoku
- przypisanie ocen sędziowskich / przypisanie oceny zero
- zakończenie procesu

**Rozwój projektu**

Model BPMN stanowi warstwę procesu biznesowego większego przedsięwzięcia analityczno-projektowego. Kolejny etap skupi się na modelowaniu systemu informatycznego w UML, obejmując komponenty odpowiedzialne za:

- zbieranie ocen sędziów
- walidację danych punktowych
- obliczanie wyników końcowych
- zarządzanie rankingami zawodów
- przechowywanie danych konkursowych

Model BPMN opisuje rzeczywistość biznesową procesu, natomiast modele UML będą przedstawiały system informatyczny wymagany do jego wsparcia i obsługi.


