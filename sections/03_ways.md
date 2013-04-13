## Viele Wege führen zum Ziel
### Arten der Verschlüsselung
### Vor- und Nachteile
### Software

<aside class="notes">
* Arten im Sinne von "Level" => Hardware > Dateisystem > "Ordner" > Datei
</aside>

---
### Arten der Verschlüsselung

* Hardwareseitig

    selbstverschlüsselnde Datenträger (SED)

    Verschlüsselungscontainer für Festplatten

* Softwareseitig

    Voll-Verschlüsselung

    „Ordner“-Verschlüsselung

    Verschlüsselung einzelner Dateien

<aside class="notes">
<p>Voll-Verschlüsselung im Sinne von Containern, die ein oder mehrere Dateisysteme
enthalten</p>
<p>Ordner-Verschlüsselung im Sinne von Einzeldateiverschlüsselung</p>
<p>Im Grunde genommen ist das ja alles das selbe…</p>
</aside>

---
### Vor- und Nachteile

* Hardwareseitig

    schnell aber teuer

    Schützt nur „offline“

* Softwareseitig

    billig, bzw ohne Zusatzkosten

    Sicherheit zu Lasten der Performance

---
### Software

* TrueCrypt

    Windows, Linux, Mac

    Vollverschlüsselung

* EncFS

    Windows, Linux, Mac(?)

    „Ordner“-Verschlüsselung

* FileVault

    Mac OS X

    Vollverschlüsselung der Benutzerdaten<br>
    (systemweit ab FileVault2 / MacOSX 10.7)

* dm-crypt / LUKS

    Linux

    Vollverschlüsselung
