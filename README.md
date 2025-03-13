# scenario-quality-checker
Aplikacja Webowa do analizy scenariuszy biznesowych.
Spring Web

Funkcje:
Liczenie kroków, podkroków kroków ze słowem kluczowym. liczenie aktorów. Upraszczanie scenariusza do danego poziomu. itp...

Przykład scenariusza:<br />
Tytuł: Dodanie książki<br />
Aktorzy:  Bibliotekarz<br />
Aktor systemowy: System<br />
<br />
• Bibliotekarz wybiera opcje dodania nowej pozycji książkowej<br />
• Wyświetla się formularz.<br />
• Bibliotekarz podaje dane książki.<br />
• IF: Bibliotekarz pragnie dodać egzemplarze książki<br />
&nbsp; &nbsp; o Bibliotekarz wybiera opcję definiowania egzemplarzy<br />
&nbsp; &nbsp; o System prezentuje zdefiniowane egzemplarze<br />
&nbsp; &nbsp; o FOR EACH egzemplarz:<br />
&nbsp; &nbsp; &nbsp; &nbsp; • Bibliotekarz wybiera opcję dodania egzemplarza<br />
&nbsp; &nbsp; &nbsp; &nbsp; • System prosi o podanie danych egzemplarza<br />
&nbsp; &nbsp; &nbsp; &nbsp; • Bibliotekarz podaje dane egzemplarza i zatwierdza.<br />
&nbsp; &nbsp; &nbsp; &nbsp; • System informuje o poprawnym dodaniu egzemplarza i prezentuje zaktualizowaną listę egzemplarzy.<br />
• Bibliotekarz zatwierdza dodanie książki.<br />
• System informuje o poprawnym dodaniu książki.
