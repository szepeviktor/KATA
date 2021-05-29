# Kisadózó vállalkozások tételes adója

Segítség KATÁ-s [vállalkozás indításához](https://www.nyilvantarto.hu/hu/evig_megkezdes)
és folytatásához távoli munkavégzés esetén.

### A KATA előnyei

- Elektronikusan kiváltható, nem kell se ügyvéd, se könyvelő
- Éves 12 millió forint bevételig havi 50 ezer forint tételes adó fizetendő
  (kb. a társasági adó mértékének fele)
- Nem kell a kiadást könyvelni, számon tartani
- Nem kell a vállalkozásnak külön bankszámlát nyitni

### Rendszerkövetelmények

1. Windows 10 Pro
1. [Java Standard Edition Version 8](https://www.java.com/en/download/manual.jsp)
   `Windows Offline (64-bit)`
1. Próbálkozás: friss [Java Standard Edition](https://www.oracle.com/java/technologies/javase-downloads.html)
   telepítése szóköz-mentes útvonalra pl. `C:\usr\java\jdk-13.0.2\`, nem pedig `C:\Program Files\Java\jdk-13.0.2\`,
   és a start.bat-ban `%PUBLIC%\abevjava\abevjava_start.bat` az alábbi módosításokkal
   - explicit Java HOME beállítása pl. `SET "ABEV_JAVA_HOME=C:\usr\java\jdk-13.0.2\bin\"`
   - Java JRE v1.11-ben eltávolított `--add-modules=java.se.ee` beállítás kitörlése

### KATÁ-s vállalkozás indítás

Főállású egyéni vállalkozóként vagy min. heti 36 órás állás mellett?
[2012. évi CXLVII. törvény 2. § 8. pontja](http://njt.hu/cgi_bin/njt_doc.cgi?docid=155155.362783#foot_8_place)

1. [E-személyi](https://eszemelyi.hu/) igénylés [Kormányablakban](https://kormanyablak.hu/hu/kormanyablakok),
   [Kobil ID Token](https://nfcshop.hu/termek/kobil-id-token-eszemelyi-olvaso/)
   USB-s NFC (mint pl. az E-személyi vagy egy chip-es bankkártya) olvasó
   és az [eSzemélyi Kliens](https://eszemelyi.hu/letoltesek) program telepítése
1. Bankszámla nyitás olyan banknál (pl. OTP), ahol van online felület és alszámlához rendelt virtuális bankkártya
1. NAV [Általános Nyomtatványkitöltő (ÁNYK)](https://www.nav.gov.hu/nav/letoltesek/nyomtatvanykitolto_programok/nyomtatvany_apeh/keretprogramok/abevjava_install.html)
   telepítése `.jnlp` fájllal,
   napló megtekintés: _Szeriz_ menü / _Megjelölés, átadás napló_
1. https://magyarorszag.hu/ [regisztráció](https://ugyfelkapu.gov.hu/regisztracio/regEszemelyi)
1. [Egyéni vállalkozói tevékenysége megkezdése](https://www.nyilvantarto.hu/ugyseged/EgyeniVallalkozassalKapcsolatosUgyInditasa.xhtml)
   [Webes ügysegéddel](https://www.nyilvantarto.hu/ugyseged/)
1. [ÖVTJ tevékenység](https://www.ksh.hu/ovtj_menu) választás:
   `62xxxx` Információ-technológiai szolgáltatás,
   [ÖVTJ kereső](https://www.ksh.hu/ovtj_kereso),
   [Egyéni vállalkozók nyilvántartása](https://www.nyilvantarto.hu/evny-lekerdezo/)
1. miért kell? [Hatósági bizonyítvány igénylése](https://www.nyilvantarto.hu/ugyseged/EgyeniVallalkozasKerelemInditasa.xhtml)
1. [Számlázz.hu](https://www.szamlazz.hu/szamla/regisztracio) regisztráció
   [autokata](https://www.szamlazz.hu/egyedi-megoldasok/autokata/) szolgáltatással
1. [MKIK (Magyar Kereskedelmi és Iparkamara) regisztráció](https://mkik.hu/gazdalkodo-szervezetek-regisztracioja),
   PDF **offline** küldése (posta vagy telefax)
1. [BPFPH (Budapest Főváros Főpolgármesteri Hivatal Adó Főosztály)](https://ssl.budapest.hu/web_hair/fszla.do)
   helyi iparűzési adó
1. [EU adószám igénylése](https://supportkata.riport.co.hu/hc/hu/articles/360019947131-EU-ad%C3%B3sz%C3%A1m-ig%C3%A9nyl%C3%A9se-autokat%C3%A1ban)
   közösségen belüli cégeknek való számlázáshoz
   Számlázz.hu autokata segítségével (20T101E nyomtatvánnyal)

### KATÁ-s vállalkozás folytatása

1. Megbízási szerződés kötés [Ptk. XXXIX. Fejezet](http://njt.hu/cgi_bin/njt_doc.cgi?docid=159096.376761)
   https://bplegal.hu/teljesites-igazolas/ A teljesítési igazolás formai követelményei
1. Mit kell könyvelni? bevétel, kiadás, mekkora keretig? EU-s bevétel/kiadás? +jogszabály
1. Évi 1 millió forint feletti bevélteleket generáló partnereknél szerződés/bevallás? +jogszabály
1. ["Tárhely"](https://tarhely.gov.hu/) átmeneti és tartós üzenetek

#### Kiadások

_ezeket a fejléceket szabatosra kéne fogalmazni_

| Költség | Hivatal | Bevallás | Összeg | Rendszeresség / Határidő |
| ------- | ------- | -------- | -----: | ------------------------ |
| tételes adó | NAV | évente egyszer, mikor? | 50 000 | havi, következő hónap 12. napjáig |
| EU-s számlák áfája? |
| kamarai hozzájárulás | MKIK | ? | 5 000 | éves, regisztrációkor |
| iparűzési adó | BPFPH | évent egyszer, mikor? | 25 000 | fél évente, ?meddig? |
| #digital szolgáltatáscsomag | Számlázz.hu | - | 18 923 + autokata 16 383 | előfizetés napjától évente |

+könyvelő
+bank
+hibrid levél
