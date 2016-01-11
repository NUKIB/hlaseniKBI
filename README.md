# Hlášení Kybernetického bezpečnostního incidentu pomocí XML formuláře
##Info
Vládní CERT ([GovCERT.CZ](www.govcert.cz)) jako součást Národního centra kybernetické bezpečnosti (NCKB) vydává schéma pro hlášení kybernetických bezpečnostních incidentů. Toto schéma lze mimo jiné použít pro tvorbu formuláře ve formátu XML, nebo jej implementovat do vlastní aplikace pro hlášení kybernetických bezpečnostních incidentů (KBI) a událostí. Jedná se o platný ekvivalent k dosavadnímu poskytovanému formuláři ve formátu PDF. Hlášení lze zasílat na cert\<dot\>incident\<at\>nbu\<dot\>cz
##Vlastnosti
Schéma je vytvořeno ve formátu XSD a pokrývá veškeré náležitosti formuláře hlášení KBI, které jsou popisovány v příloze č. 5 ve [vyhlášce 316/2014 Sb](https://www.nbu.cz/download/nodeid-1067/). o bezpečnostních opatřeních, kybernetických bezpečnostních incidentech, reaktivních opatřeních a o stanovení náležitostí podání v oblasti kybernetické bezpečnosti (vyhláška o kybernetické bezpečnosti). Navíc obsahuje i položky, které nejsou ve vyhlášce uvedeny, ale přispívají k lepší a efektivnější výměně potřebných informací pro následné řešení, či vyhodnocení hlášené události.

Toto schéma přehledně definuje, jak mají jednotlivá pole formuláře vypadat a v jakém formátu mohou být vyplněna.
##Obsah
- hlaseniKBI_1.0.xml
- hlaseniKBI_1.0.xsd

XSD soubor slouží pro validaci XML formuláře na hlášení kybernetických
bezpečnostních incidentů. Přiloženo je i modelové hlášení
**hlaseniKBI_1.0.xml**.

##Nástroje
###Linux shell
Při přípravě hlášení pomocí XML souboru si můžete ověřit, že Vámi
připravený soubor je validní např. pomocí nástroje `xmllint`:

```shell
$ xmllint --noout --schema hlaseniKBI_1.0.xsd hlaseniKBI_1.0.xml  
hlaseniKBI_1.0.xml validates  
$  
```
