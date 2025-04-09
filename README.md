Datanraavinta sisältää 2 eri cutoff kohtaa, mikä estää vahingollisen datan hävityksen:

1. Koulutusdata raavitaan tiedostoon 'myyntihinnat_TRE_new.csv' ja se puolestaan luetaan sisään tiedostosta 'myyntihinnat_TRE_original.csv'

2. Testidataa raavitaan kansioon 'hinta_data', josta se luetaan. Myynti-ilmoituksia raapiva blokki on kommentoitu pois käytöstä, tämän voi ottaa käyttöön poistamalla kommentit, mikäli haluaa noutaa uusimmat ilmoitukset.
