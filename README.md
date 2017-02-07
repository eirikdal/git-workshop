N.B. For oppgave 1 til og med 4 kan du utfoere i samme repo som du lager i ex01.
Repoene i ex02, ex03, ex04 er kun dersom du staar fast, men har lyst til aa forsoeke deg paa oppgavene videre.

ex01 - Lag et repository uten aa bruke "git init" [enkel]
ex02 - Legg en fil i staging area uten aa lage en fil, og uten aa bruke "git add" [enkel]
ex03 - Lag minst 2 commits paa master uten aa bruke "git add" og "git commit" [enkel]
ex04 - Lag en ny branch med minst en commit uten aa bruke "git add", "git commit" eller "git checkout" [enkel]
ex05 - Bjarne oppdager til sin store forundring at Git lager kopier av alle filene hans i stedet for aa lagre kun endringene. Hjelp han aa finne ut av problemet [enkel]
ex06 - Bjarne har mistet en commit. Hjelp han aa finne den igjen og legg den paa master (medium)
ex07 - Freddy Hipster har lagt sin private ssh noekkel i repo, og naa trenger han din hjelp til aa finne den igjen. [medium]
ex08 - Freddy Hipster angrer dypt paa at han committet sin private ssh noekkel i et opensource github repo. Kan du hjelpe han aa fjerne den fra historikken helt? [vanskelig]
ex09 - Lag en (light-weight) tag som peker paa en commit i repo som du opprettet i ex01-ex04. [enkel]

bonus01 - Du har gjort en commit og vil gjerne pushe denne til master, men Git vil ikke la deg pushe. Finn ut hva som er feil og fiks det!
bonus02 - Du og din kollega jobber paa et prosjekt og du har nettopp gjort en endring som du gjerne vil pushe til Git, men Git lar deg ikke pushe. Finn ut hva som er feil og fiks det!
bonus03 - Som en god soldat saa er du disiplinert og committer ofte. Naa er det tid for aa pushe, men foerst vil du rydde litt i historikken..
bonus04 - Bjarne har lagd en feature-branch, men han har gjort noe feil. Egentlig ville han branche ut fra master, men naa er alt galt. Hjelp han aa loese problemet..
bonus05 - Bjarne har ved et uhell committet en stor fil til repo. Finn ut hvordan du kan fjerne denne fra historikken. [vanskelig]

Hint:

Gitkommandoer du maa kjenne til for aa lose disse oppgavene inkluderer:

* git help <command>
* git update-index (extra hint: <<100644>)
* git write-tree
* git hash-object (extra hint: --stdin, -w)
* git update-ref (valgfri)

* git filter-branch
* git prune

Nyttige kommandoer, men ikke noedvendige for aa kunne loese oppgavene:

* git cat-file
* git rev-list
* git verify-pack
* git count-objects
* git fsck
