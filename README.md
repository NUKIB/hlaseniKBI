# Hlášení Kybernetického bezpečnostního incidentu pomocí XML formuláře

Repozitář obsahuje

- hlaseniKBI_1.0.xml
- hlaseniKBI_1.0.xsd

XSD soubor slouží pro validaci XML formuláře na hlášení kybernetických
bezpečnostních incidentů. Přiloženo je i modelové hlášení
**hlaseniKBI_1.0.xml**.

Při přípravě hlášení pomocí XML souboru si můžete ověřit, že Vámi
připravený soubor je validní např. pomocí nástroje `xmllint`:

```
$ xmllint --noout --schema hlaseniKBI_1.0.xsd hlaseniKBI_1.0.xml  
hlaseniKBI_1.0.xml validates  
$  
```
