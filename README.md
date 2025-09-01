# OK-tiimi
Ohjelmistoprojekti 1-kurssin OK-tiimin harjoitusrepositorio
Scrum Ohjeen tekoa

- Tässä kävi konflikti... 

Ongelmat :

Projektin aikana muokkasin README.md-tiedostoa, ja kun yritin tuoda development-haaran muutokset main-haaraan, Git ilmoitti merge-konfliktista. Konflikti syntyi, koska sekä main- että development-haara olivat muokanneet samaa tiedoston kohtaa.

Tämän seurauksena::

Git ei voi automaattisesti yhdistää samoja rivejä, ja silloin on itse ratkaistava, mitä sisältöä säilytetään.

Konfliktin ratkaiseminen vaatii :

katsotaan molempien haarojen muutokset

päätetään, mitä tekstiä pidetään

poistetaan konfliktimerkinnät (<<<<<<<, =======, >>>>>>>)

Ratkaistuaan konfliktin tiedoston voi lisätä staging-alueelle (git add) ja tehdä commitin, jolloin merge valmistuu.


Commitit esimerkkinä:

git commit -m "Lisätty Scrum-opas: Scrum-syklin yleiskuvaus"

git commit -m "Päivitetty README.md: lisätty sprintit-osio"

git commit -m "Ratkaistu merge-konflikti main <- development"