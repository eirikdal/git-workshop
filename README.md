# Git plumbing 101

*N.B. For oppgave 1 til og med 4 kan du utføre i samme repo som du lager i ex01.
Repoene i ex02, ex03, ex04 er kun dersom du står fast, men har lyst til å forsøke deg på oppgavene videre.*

Forsøk å løse disse oppgavene uten å bruke Google. Bruk manpages eller "Git help" for å løse oppgavene.
___

ex01 - Lag et repository uten å bruke "git init" [enkel]

ex02 - Legg en fil i staging area uten å lage en fil, og uten å bruke "git add" [enkel]

ex03 - Lag minst 2 commits på master uten å bruke "git add" og "git commit" [enkel]

ex04 - Lag en ny branch med minst en commit uten å bruke "git add", "git commit" eller "git checkout" [enkel]

ex05 - Bjarne oppdager til sin store forundring at Git lager kopier av alle filene hans i stedet for å lagre kun endringene. Hjelp han å finne ut av problemet [enkel]

ex06 - Bjarne har mistet en commit. Hjelp han å finne den igjen og flytte den til master uten å recommitte (medium)

ex07 - Freddy Hipster har lagt sin private ssh nøkkel i repo, og nå trenger han din hjelp til å finne den igjen. [medium]

ex07a - Klok av skade har Freddy har kommet opp med en ny og lur for å finne igjen SSH nøkkelen sin i repo. Hva har han gjort? [enkel/medium]

ex08 - Freddy Hipster angrer dypt på at han committet sin private ssh nøkkel i et opensource github repo. Kan du hjelpe han å fjerne den fra historikken helt? [vanskelig]

ex09 - Lag en light-weight tag (uten å bruke "git tag") som peker på en commit i repo som du opprettet i ex01-ex04. [enkel]

### Bonusoppgaver 

bonus01 - Du har gjort en commit og vil gjerne pushe denne til master, men Git vil ikke la deg pushe. Finn ut hva som er feil og fiks det!

bonus02 - Du og din kollega jobber på et prosjekt og du har nettopp gjort en endring som du gjerne vil pushe til Git, men Git lar deg ikke pushe. Finn ut hva som er feil og fiks det!

bonus03 - Som en god soldat så er du disiplinert og committer ofte. Nå er det tid for å pushe, men først vil du rydde litt i historikken..

bonus04 - Bjarne har lagd en feature-branch, men han har gjort noe feil. Egentlig ville han branche ut fra master, men nå er alt galt. Hjelp han å løse problemet.. 

bonus05 - Bjarne har ved et uhell committet en stor fil til repo. Finn ut hvordan du kan fjerne denne fra historikken. [vanskelig]

#### Alternativ 1: Siste utfordring

Du har ødelagt Git, men du trenger desperat et repo med en branch og en commit. Du har ikke tilgang til internett, så du får ikke lastet ned en
ny versjon. Lag et Git repo uten å bruke Git i det hele tatt.

Repoet skal ha minst: 

* 3 commits
* 2 branches
* 3 trær
* 1 tag

Se data-model-4.png for eksempel.

Det er lov å bruke Git for å verifisere at repoet ditt fungerer.

#### Alternativ 2: Gitklient

Lag din egen Git klient i valgfritt språk. Denne skal klare å:

* Opprette nytt repo (ingen andre krav til repo annet enn at Git skal kunne gjenkjenne det)
* Adde fil til staging area
* Lage commit av innholdet i staging area

Det er ingen krav til at programmet må være brukervennlig.


## Hints:

Gitkommandoer du må kjenne til for å lose disse oppgavene inkluderer:

* git help <command>
* git update-index (extra hint: <mode> = 100644)
* git write-tree
* git hash-object (extra hint: --stdin, -w)
* git update-ref (valgfri)

* git filter-branch
* git prune

Nyttige kommandoer, men ikke nødvendige for å kunne løse oppgavene:

* git cat-file
* git rev-list
* git verify-pack
* git count-objects
* git fsck
