# Andmekooseisud

## Andmekooseisude koodid
EE0401001 - Veevõtuandmed vee erikasutusõiguse tasu deklareerimiseks
EE0401002 - Reo- ja heitveeandmed veesaastetasu deklareerimiseks
EE0401003 - Veekasutuse andmed keskkonnaaruandluseks
EE0401004 - Veevaldkonna majandustegevuse andmed keskkonnaaruandluseks

Andmekoosseisude valik sõltub andmeesitaja tüübist.
- Vee-ettevõtja (kõik andmed)
- Veekasutaja (va andmed:  ..)
- Veejuhtija (va andmed: .. )
- Vesiviljeleja (kaks andmesektsiooni: )
- Süvendaja ja/või kaadaja (kaks andmesektsiooni: )

- Võib esineda nullaruanne


## EE0401001 struktuur (Veevõtuandmed)

- Põhjaveevõtu korral lisada põhjaveehaare (kood ja nimetus). 
- Kui haarde koht on puurkaev siis ka ADS
- Lisada märkus, kas ammutatud vett töödeldakse või mitte. Veetöötlusseadmete andmed võetakse veetöötlusjaamade registrist.

### lisainfo veetöötlusjaamade kohta
- kood
- nimetus
- tehnilised parameetrid (ei ole millegipärast asukoha ja veehaarde andmeid)



## EE0401002 struktuur




## EE0401003 struktuur (Veekasutuse andmed keskkonnaaruandluseks)



Esitatavad andmed
- Asula, kus elanikele veeteenuseid pakutakse


### Reoveepuhastite loetelu
- Kood
- Nimetus
- Purgitava reovee kogus (ie ja m3/a)
- mis reoveepuhastusalaga seotud

### Torustiku lisainfo
- Torustiku liik (ühisveevärk, kansalistatsioon, sademeevesi)
- kogupikkus
- ühiskanalisatsiooni puhul ka liik (loend)
- torustiku lekete %

### Lekete lisainfo
- lekete registreerimise meetmed
- lekete ennetamise meetmed


### Üksikud andmeväljad

- Kas toimus loapõhine tegevus? Mitteloapõhiuse korral lisada selgitus (lisaväli)

**Ühisveevärgiteenus**
1. Ühisveevärgiteenuse liitumispunktide koguarv
2. Ühisveevärgiteenusega liitunud liitumispunktide arv
3. Ühisveevärgiteenust kasutavate elanike osakaal (%) hinnanguline näitaja
4. Ühisveevärgiteenuga liitumise võimalusega elanike osakaal (%) hinnanguline näitaja

**Ühiskanalisatsiooniteenus**
1. Ühiskanalisatsiooniteenuse liitumispunktide koguarv
2. Ühiskanalisatsiooniteenusega liitunud liitumispunktide arv
3. ÜÜhiskanalisatsiooniteenust kasutavate elanike osakaal (%) hinnanguline näitaja
4. Ühiskanalisatsiooniteenuga liitumise võimalusega elanike osakaal (%) hinnanguline näitaja

### Müügi puhul esitada
- abonomenttasude eratarbijale
- Joogivee hind eratarbijale (eur/m3)
- Kanalisatsiooni hind eratarbijale (eur/m3)

- müüdud jooguvee kogus
- vastuvõetud reovee kogus
- loaga seotud tegevusala müügitulu

### Investeeringute koguinfo
- investeeringud (omafinantseering) ühisveevärgisüsteemidesse
- investeeringud (omafinantseering) ühiskanalisatsioonisüsteemidesse

Põhivara omafinantseering = põhivara soetus - põhivara sihtfinantseeringu tulu
Muud finantseeringud = põhivara sihtfinantseeringu tulu

Sisult tuleb saata majandustegingute pealt põhivara soetused rajatiste gruppide lõikes ja saadud sihtfinantseeringud rajatiste gruppide lõikes.
Eraldi lisada põhivara soetusega seotud km kulu, kui seda ei saa tagasi küsida.

### Investeeringute plaan (eelarve moodulist)
- plaanitavad investeeringute mahud kokku järgneva kolme aasta jooksul

### Veekasutuse lisakogused (müügi põhjal?)
- lisaks tuleb esitada veekasutuse andmed kategooriate kaupa
    - Olme (elanikud), Tööstus, Energeetika, Jahutus, Põllumajandus, Niisutus, Muu, Veekadu.

### Teiste arundluskohustustega vahetatud vesi
- tehingupartner, vee liik ja kogus (m3/a) +/- (saadav ja antav vesi)

## EE0401004 struktuur


