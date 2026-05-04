# h6_miniprojekti
This is a homepage repo for task h6 "miniprojekti". 

*This project was made as part of a Finnish school course, so it was written in Finnish.*

## Linux-työpisteen automaattinen esivalmistelu Ansiblella

Ajon jälkeen työpisteellä valmiina:

- Valmis hakemistorakenne
- Tarvittavat paketit asennettuna
- Tarvittavat tiedostot
- Alias-komennot



Projektiin tarvittavat tarkat ominaisuudet:
- pakettien asennus: tree, micro, bash-completion, caddy, git
- Hakemistojen luonti
- Alias-kommenot .bashrc -tiedostoon
- Welcome.txt kopiointi kotihakemistoon
- Caddy:n asennus (+state ja enabled) konfiguraatio ja handler restart
- Git repon kloonaus HTTPS















Termien selitykset:

Idempotenssi = Ajaessa muutoksia tapahtuu vain, jos järjestelmä ei ole jo halutussa tilassa.

Infrastruktuuri koodina = Ohjelmoitu käyttäen YAML-merkintäkieltä ja versioitu Gitillä.

Yksi totuus = Halutut asetukset määritelty yhteen Ansiblen playbookiin ja lopputulos on aina sama.
