# __API__
API står for = Application Programming Interface(nodejs-manual, brugsforvirring)

Web service API = Et API hvor man kan slå ting op i en database.


REST = REpresentational State Transport

Restful = 

Request Method(s): GET - POST - PUT - DELETE (de 4 kaldes også HTTP verber)

_Request method bestemmer hvad vi gør, men adressen er den samme_

GET = Henter data
POST = Sende data ud/afsted, oprette noget nyt
PUT = Opdatere/ændre en eksisterende ressource
DELETE = Sletter eksisterende ressource

* Resurser er de resultater der kommer ud (json, en repræsentation af en resurse).
* Resurser er det der står efter api adressen, også kaldet endpoint, som leder til en ressource og i programmering/kodning kaldes det et route.

__Vi har kun data ét sted, som flere kan hente fra istedet for at skulle kopiere json filen fra sted til sted.__


# __Dokumentation__
_sker i jsdoc og man starter en kommentar med /**. - mere info om jsdoc findes på usejsdoc.org_

* Funktioner:
    * Navn
    * Formål
    * Parametre
    * Return

* API:
    * Ressourcenavn
    * Formatering

* Changelog: