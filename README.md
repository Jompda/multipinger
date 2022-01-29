# multipinger
Shell scripti linuxille, joka näyttää kohteiden tilan verkossa.

## Käyttöohje
Kohteet erotetaan välilyönnein ja kohde on joko raaka IP-osoite, domainnimi tai nimi=IP-osoite

Esimerkkejä:<br>
Kohde 1.0.0.1 `./multipinger 1.0.0.1`<br>
Kohteina 1.0.0.1 ja localhost `./multipinger 1.0.0.1 localhost`<br>
Kohteina 1.0.0.1 ja localhost, mutta 1.0.0.1 on uudelleennimetty `./multipinger Eka=1.0.0.1 localhost`<br>

Kohteita ei tarvitse aina erikseen kirjoittaa argumentteina vaan ne voidaan kirjoittaa valmiiksi tiedostoon, jossa ne erotetaan rivivaihdoin.<br>
Tällöin ohjelma ajetaan komennolla `./multipingerf TIEDOSTONIMI`.<br><br>
Ikkunan voi pakata pienimpään mahdolliseen tilaan painamalla R-painiketta.
