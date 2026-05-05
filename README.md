# h6_miniprojekti - Nico Defaa & Joonas Kalliokoski
This is a homepage repo for task h6 "miniprojekti". 

*This project was made as part of a Finnish school course, so it was written in Finnish.*

## Linux-työpisteen automaattinen esivalmistelu Ansiblella

Ajon jälkeen työpisteellä valmiina:

- Valmis hakemistorakenne
- Tarvittavat paketit asennettuna
- Tarvittavat tiedostot

Tehtävät toimenpiteet:
- Luodaan ryhmä "kayttajat"
- Luodaan käyttäjä "kayttaja" kotihakemistoineen, ja lisätään ryhmään "kayttajat"
- Asennetaan paketit: micro, tree, bash-completion, git, caddy
- Luodaan welcome.txt -tekstitiedosto käyttäjän "kayttaja" kotihakemistoon
- Luodaan hakemistot work/project1 ja work/project2 käyttäjän "kayttaja" kotihakemistoon
- Kopioidaan verkkopalvelimen oletussivu kohdekoneelle
- Varmistetaan verkkopalvelimen (caddy) päälläolo

<br>

*Kohdekoneet on listattu hosts.ini -tiedostossa. Nykyiset asetukset on muutettava omiin koneisiisi sopiviksi. Kohdekoneelle on lisätty SSH:n julkinen avain ~/.ssh/authorized_keys -tiedostoon.*

<img width="378" height="157" alt="kuva" src="https://github.com/user-attachments/assets/0d325124-5d47-485f-b375-b4b7042a073d" />

<br>


## Valmiin playbookin ajaminen:

*Ensimmäinen playbook-ajo.*

<img width="1327" height="854" alt="kuva" src="https://github.com/user-attachments/assets/7a1cc3b7-f65e-44b1-bd94-f5dbff4cc784" />

<br>
<br>
<br>

*Toinen playbook-ajo: idempotentti.*

<img width="1329" height="850" alt="kuva" src="https://github.com/user-attachments/assets/c375c231-a8a9-48e0-ad6d-994fbd665cdd" />

<br>
<br>
<br>

*Lopputulos kohdekoneen kayttaja-tilillä.*

<img width="496" height="245" alt="kuva" src="https://github.com/user-attachments/assets/cc2a6ed0-a31f-45f3-bfcb-f66551fcc616" />


<br>
<br>

## Dokumentaatio

*Ansiblen hakemistopuu*

<img width="325" height="456" alt="kuva" src="https://github.com/user-attachments/assets/05f70378-571c-4ac7-92cf-552989766921" />

<br>

*roles/caddy/*

<img width="673" height="392" alt="kuva" src="https://github.com/user-attachments/assets/034ee8fe-56b7-40fc-bd2a-1bff4a4cd1bf" />

<br>

*roles/file/*

<img width="543" height="554" alt="kuva" src="https://github.com/user-attachments/assets/ea065548-34bf-4e28-b7a5-e3880dccc46d" />

<br>

*roles/package/*

<img width="478" height="187" alt="kuva" src="https://github.com/user-attachments/assets/e426de09-a788-43c5-93d6-a91af1b5511b" />

<br>

*roles/users/*

<img width="596" height="440" alt="kuva" src="https://github.com/user-attachments/assets/a95b219d-0200-4219-b757-1788f85285a6" />

<br>

*ansible.cfg & hosts.ini*

<img width="360" height="354" alt="kuva" src="https://github.com/user-attachments/assets/5f0b45cd-9cce-4056-8fbb-01c61d80ce91" />
