# Założenia

## Zgłoszenie brane na sprint powinno mieć:
- podpięty sprint - Iteration Path

e-UrzadProject\Sprint [numer sprintu]
- podpiętą strefę - Area Path

e-UrzadProject\e-Urzad\\[nazwa zespołu]
- wycenę
- odpowiedni tag
- stworzone taski z konkretnym opisem
- odpowiednią priorytetyzację

# Tagi
S[numer sprintu]Candidate - zarezerwowany dla zgłoszeń **objętych** planowaniem. Tego tagu używamy **wyłącznie** przy planowanych zadaniach.

S[numer sprintu]Add - zarezerowany dla zgłoszeń **nieobjętych** planowaniem, dodanych podczas trwania sprintu.

JIRA - zarezerwowane dla zgłoszeń przepisanych z JIRY.

# Przepływ

## User Story
![Screenshot](us%20flow.png)

## Bug
![Screenshot](bug%20flow.png)

# Realizacja

Po skończonej realizacji każde zgłoszenie powinno mieć uzupełnione godziny oraz w statusie In Review przepięte na testera.

# Podsumowanie

Jako placeholder uznaje się Dev Leadera. Każde nowo powstałe zgłoszenie powinno przejść przez weryfikację PM'a oraz Dev Ledera, zostać prawidłowo dopasowane według założeń. Nie powinniśmy manipulować odpinaniem zadań ze sprintu podczas jego trwania. Każde zgłoszenie niezależnie od typu (bug, user story) powinno mieć child w postaci taska. Pull request realizacji zgłoszenia powinien mieć podlinkowane jego taski. 
