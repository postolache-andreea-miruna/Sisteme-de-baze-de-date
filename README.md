# Gestionarea rezultatelor sportivilor dintr-un club la competii
Proiect Master an 1

 Cerinţe proiect:
 1. Prezentarea concisă a bazei de date (utilizarea ei).
 2. Realizarea diagramei entitate-relație (ERD): entitățile, relațiile și atributele trebuie 
definite în limba română.
 3. Realizarea diagramei conceptuale pornind de la diagrama entitate-relație.
 4. Transformarea sistemului conceptual într-un design logic, subliniind relaţiile dintre 
tabele, cheile primare şi străine (externe).
 5. Transformarea design-ului logic într-un design fizic astfel încât sistemul rezultat la 
punctul 4 să fie în FN3. 
 • Dați un exemplu de atribut repetitiv (multivaloare) al unei entități din diagramă.

 • Dați un exemplu de tabel relațional din diagramă care este în FN1, dar nu în FN2. 
Să se aducă tabelul în FN2.

 • Dați un exemplu de tabel relațional din diagramă care este în FN2, dar nu în FN3.  
Să se aducă tabelul în FN3.

 6. Implementarea tabelelor în Oracle, folosind chei primare, constrângeri de referinţă şi 
domeniu. Adăugarea de informații coerente (minim 5 înregistrări pentru fiecare entitate 
independentă; minim 10 înregistrări pentru tabela asociativă).

 7. Scrierea a 15 interogări, cât mai complexe, care să ilustreze toate aspectele învăţate din 
lista (formulați în limbaj natural problemele ce urmează a fi rezolvate):

 • clauzele GROUP BY, HAVING, START WITH, CONNECT BY, ORDER BY;

 • funcţii pentru lucrul cu şiruri de caractere şi date calendaristice: LOWER, UPPER, 
SUBSTR, INSTR, TO_CHAR, TO_DATE, ADD_MONTHS, MONTHS_BETWEEN;

 • funcții diverse: DECODE, NVL, NULLIF, CASE;
 
 • INNER, LEFT, RIGHT, FULL JOIN;
 
 • operatori pe mulțimi;
 
 • funcţii multiple-row/ agregat: AVG, SUM, MIN, MAX, COUNT;
 
 • subinterogări în clauzele: SELECT, FROM, WHERE, HAVING;
 
 • operatorul DIVISION.
 
 8. Crearea un tabel de mesaje 
 9. Ilustrarea următoarelor noţiuni de PL / SQL (formulați în limbaj natural problemele ce 
urmează a fi rezolvate):

 • subprogram stocat independent (inclusiv apelare) care să utilizeze toate cele 3 tipuri de 
colecții învăţate;

 • subprogram stocat independent (inclusiv apelare) care să utilizeze 2 tipuri de cursoare 
învățate, unul dintre acestea fiind cursor parametrizat, dependent de celălalt cursor;

 • subprogram stocat independent de tip funcție care să utilizeze într-o singură comandă 
SQL 3 dintre tabelele definite; tratarea tuturor excepțiilor care pot apărea (definiți 
minim 2 excepții proprii); apelarea subprogramului astfel încât să fie evidențiate toate 
cazurile tratate;

 • Trigger de tip LMD la nivel de comandă (inclusiv declanșare);
 
 • Trigger de tip LMD la nivel de linie (inclusiv declanșare);
 
 • Trigger de tip LDD (inclusiv declanșare).
 
 • Pachet care să conțină toate obiectele definite în cadrul punctului 9 (inclusiv apelarea 
lor). 

10. În cazul obţinerii unor excepţii, dacă doriţi să înregistraţi unele avertismente sau alte 
informaţii, mesajele corespunzătoare vor fi inserate în tabelul MESAJE (id-ul mesajului 
se va insera automat folosind o secvenţă).
