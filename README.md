# h6_miniprojekti - Nico Defaa & Joonas Kalliokoski
This is a homepage repo for task h6 "miniprojekti". 

*This project was made as part of a Finnish school course, so it was written in Finnish.*

## Linux-työpisteen automaattinen esivalmistelu Ansiblella

Ajon jälkeen työpisteellä valmiina:

- Valmis hakemistorakenne
- Tarvittavat paketit asennettuna
- Tarvittavat tiedostot


Projektiin tarvittavat tarkat ominaisuudet:
- pakettien asennus: tree, micro, bash-completion, caddy, git
- Hakemistojen luonti
- Welcome.txt kopiointi kotihakemistoon
- Caddy:n asennus (+state ja enabled) konfiguraatio ja handler restart

## Valmiin playbookin ajaminen:

*Ensimmäinen playbook-ajo.*

<img width="1327" height="854" alt="kuva" src="https://github.com/user-attachments/assets/7a1cc3b7-f65e-44b1-bd94-f5dbff4cc784" />

<br>
*Toinen playbook-ajo: idempotentti.*

<img width="1329" height="850" alt="kuva" src="https://github.com/user-attachments/assets/c375c231-a8a9-48e0-ad6d-994fbd665cdd" />


*Lopputulos kohdekoneen kayttaja-tilillä.*

<img width="505" height="214" alt="kuva" src="https://github.com/user-attachments/assets/254854ea-1199-434a-86c7-15b46a4d6cbf" />













Termien selitykset:

Idempotenssi = Ajaessa muutoksia tapahtuu vain, jos järjestelmä ei ole jo halutussa tilassa.

Infrastruktuuri koodina = Ohjelmoitu käyttäen YAML-merkintäkieltä ja versioitu Gitillä.

Yksi totuus = Halutut asetukset määritelty yhteen Ansiblen playbookiin ja lopputulos on aina sama.
