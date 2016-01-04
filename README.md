# Hlášení Kybernetického bezpečnostního incidentu pomocí XML formuláře

Repozitář obsahuje

- hlaseniKBI.xml
- hlaseniKBI.xsd

XSD soubor slouží pro validaci XML formuláře na hlášení kybernetických
bezpečnostních incidentů. Přiloženo je i modelové hlášení
**hlaseniKBI.xml**.

Při přípravě hlášení pomocí XML souboru si můžete ověřit, že Vámi
připravený soubor je validní např. pomocí nástroje `xmllint`:

```
$ xmllint --noout --schema hlaseniKBI.xsd hlaseniKBI.xml  
hlaseniKBI.xml validates  
$  
```
