
# 2. kodutöö – ToDo rakendus

Autorid: Mihkel Vaher, Raner Rebane, Gevin Paas

Funktsionaalsus: 
1) On võimalik otsida Ülesannete seast kindlat ülesannet.
2) Kui ülesande tähtaeg on möödunud ja see on tegemata, siis taustavärv läheb punaseks.
3) Kasutaja näeb ülesande lisamisel üleval täpset kellaaega koos kuupäevaga.
4) Kasutajal on võimalik sorteerida ülesandeid nime ja kuupäeva alusel.
5) Kasutajal on võimalik kustutada ning märkida tehtuks ülesanne.
6) Kui kasutaja ei ole täitnud kõiki vajalikke lahtreid, ilmub veateade, mis kustub 2sekundi pärast.
7) Kui lisad uue Todo, siis läheb tööle muusika.


### Tähtpäev 05.04.2020 23:59

## Nõuded

1. Töö tuleb teha vähemalt kahekesi, eelnevalt kokkuleppel on lubatud ka kolm liiget. GitHub'is peab eristuma, kes mida tegi!
1. README.md fail sisaldab (1 punkti):
    * autorite nimesid; 
    * kirjeldust tekkinud keerukustest
    * funktsionaalsuste kirjeldust
1. Todo rakenduse funktsionaalsused:   
    * Saab lisad ja kustutada (1 punkt)
    * Saab märkida ülesandeid tehtuks (1 punkt)
    * Saab järjestada kuupäeva ja nime järgi ülesandeid (2 punkti)
    * Ülesanded salvestatakse localStorage'isse ja faili/andmebaasi (2 punkti)
    * Ülesannete salvestamiseks ja kuvamiseks kasutatakse AJAX-it (1 punkti)
    * Kui kasutaja tuleb lehele, siis näidatakse varem salvestatud ülesandeid (1 punkt)
    * Rakendus töötab loogiliselt ja kasutaja ei pea mõtlema, et kuidas rakendus töötab. (2 punkti)
    * Lisa ise 5 funktsionaalsust juurde.(5 punkti)
      Näiteks: 
         * Võimalus lisada kategooriad ja nende alusel jagada ülesandeid
         * Möödunud ja/või tänase kuupäevaga tegemata ülesanded märkida erinevalt
         * Võimalus otsida ülesandeid
         * Võimalus märkida ülesandeid tähtsaks ning kuvada tähtsad ülesanded eraldi listina
1. Väljanägemine ja animatsioonid
    * Rakendus näeb kena välja (3 punkti)
    * Elementide kuvamisel/eemaldamisel on kasutatud jQuery animatsioone (1 punkt)


## Githubi töövoog grupiga töötades

1. Üks grupi liikmetest teeb fork-i 2kodutoo repositooriumist
2. Tuleb lisada meeskonnaliikmed collaborators-iteks fork-itud repositooriumi 
3. Collaborator-id peavad kutsega nõustuma (e-mail)
4. Iga ühel tuleb teha git clone fork-itud repositooriumist (git clone https://YOURUSERNAME@github.com/REPOSITORYOWNERUSERNAME/REPOSITORY.git)
5. Muudatuste lisamine:
     * git add
     * git commit
     * git fetch & pull
     * git push

## Kasulikud viited
* [JQuery dokumentatsioon](http://api.jquery.com)
* [Collaboration on github](https://github.com/eesrakenduste-arendamine-2019/2kodutoo/settings/collaboration)
* [JQuery POST](https://api.jquery.com/jquery.post/)
* [JQuery AJAX](http://api.jquery.com/jquery.ajax/)
