# Freedom
Lincenses, greps and pipes

## Vapaa ohjelmisto

Karkeasti ottaen vapaa ohjelmisto tarkoittaa, että käyttäjillä on vapaus käyttää, kopioida, jakaa, tutkia, muuttaa ja parantaa ohjelmistoa. 
Ohjelma on ilmainen ohjelmisto, jos ohjelman käyttäjillä on neljä keskeistä vapautta:

  - Vapaus ajaa ohjelmaa haluamallasi tavalla mihin tahansa tarkoitukseen.
  - Vapaus tutkia ohjelman toimintaa ja muuttaa sitä niin, että se suorittaa tietokoneesi haluamallasi tavalla. Pääsy lähdekoodiin on tämän edellytys.
  - Vapaus jakaa kopioita, jotta voit auttaa muita. 
  - Vapaus jakaa kopioita muokatuista versioistasi muille. Tekemällä tämän voit antaa koko yhteisölle mahdollisuuden hyötyä muutoksistasi. 
    Pääsy lähdekoodiin on tämän edellytys. 
 Lähde: https://www.gnu.org/philosophy/free-sw.html 
 
 ## Mikä tekee lisenssistä avoimen lähdekoodin
  
 - Peruslogiikka on, että yksinoikeudet käännetään ei-yksinoikeudellisiksi. Kaikki tärkeimmät tekijänoikeuden osat, kopiointi, jakelu ja muokkaaminen on ehdottomasti sallittava avoimen lähdekoodin lisensseissä. Tämä on ristiriidassa ohjelmistoteollisuuden perinteisen immateriaalioikeuksia ja lisensointia koskevan ajattelun kanssa.
 - On korostettava, että avoin lähdekoodi ei ole millään tavalla tekijänoikeuden vastaista. Ohjelmiston lisensointi avoimen lähdekoodin lisenssillä ei tarkoita, että ohjelmisto lahjoittaisi yleiseen käyttöön. Avoimen lähdekoodin ohjelmistoilla on edelleen omistajia niin kauan kuin tekijänoikeus on voimassa.
 
 ### Mitä ei vaadita?
 
  - Moraaliset oikeudet. Avoimen lähdekoodin määritelmä ei puhu määräyksistä eikä maineesta. Epäilemättä useimpien maiden tekijänoikeuslaki vaatii esimerkiksi, 
    että tekijän nimeä ei poisteta johdannaisteoksesta.
  - Patentti- ja muut immateriaalioikeudet. Avoimen lähdekoodin määritelmä asettaa olennaisesti tekijänoikeuksia koskevia vaatimuksia, mutta ei muita
    immateriaalioikeuksia. Patenteista määritelmä ei puhu.
  - Hallittu oikeuksien omistus. Avoimen lähdekoodin lisenssit eivät vaadi valvottua oikeuksien omistajuutta, mutta sallivat hajautetut ja hajanaiset oikeudet.
  - Takuut. Määritelmä ei myöskään vaadi mitään takuista. Tämä on itse asiassa järkevää, koska sekä teknisten (virhe) että juridisten (korvaus) takuiden myynti voi
    olla. 
    lisätulolähde kaupallisille avoimen lähdekoodin kehittäjille. 
  - Yhteensopivuus. Avoimen lähdekoodin määritelmä asettaa vain kriteerit ohjelmistolisenssien sertifioimiseksi. 
  - Muodollisuudet. Lopuksi määritelmä ei edellytä, että lisenssien pitäisi olla oikeudellisesti sitovia tai täytäntöönpanokelpoisia.
    
### Avoimen lähdekoodin sopimuksen täytäntöönpano

 - Laki teoria. Niin kauan kuin ohjelmistolisenssejä on käytetty, on väitetty, että tällaiset lisenssisopimukset eivät välttämättä ole täytäntöönpanokelpoisia,
   koska käyttäjä ei välttämättä harkitse ja nimenomaisesti hyväksy lisenssiä. Monet avoimen lähdekoodin lisenssien kommentoijat kuitenkin väittävät, että
   lisenssit todellakin tulevat käyttöönottokelpoisiksi, kun käyttäjä levittää teosta edelleen. Levittämistä rajoittaa tekijänoikeus, kunnes lisenssi on hyväksytty. 
 - Para-oikeudellinen käytäntö. On oltava varovainen, ettei ylikorosteta laillisen täytäntöönpanon roolia. Vaikka se voi olla nopea ja tehokas ja kattaa 
   useimmat lisenssien noudattamiseen liittyvät ongelmat tiiviissä kehittäjäyhteisössä, sen ulottuvuus on silti rajallinen. 
   
### Lisenssit luokiteltu

 - Toiminnalliset erot. Toiminnallisesta näkökulmasta avoimen lähdekoodin lisenssit voidaan luokitella sen mukaan, miten kukin lisenssi käsittelee lähdekoodin
   muokkausoikeutta. 
     - Normaali vastavuoroisuusvelvoite tarkoittaa, että lähdekoodin jakeluehdot on säilytettävä. 
     - Vahva vastavuoroisuusvelvoite laajentaa normaalia versiota. Adaptaatioiden ja johdannaisten on säilytettävä lisenssiehdot ennallaan. 

 Lähde: http://lib.tkk.fi/Diss/2005/isbn9529187793/isbn9529187793.pdf 
 
Melko tiiviiksi yritin näitä lainauksia käännellä molemmilta sivustoilta, mutta yllättävän paljon tekstin piitudet venyivät. Toisekseen se, että kuinka paljon näissä teksteissä on ns. ylimäärästä jargonia, vaikea sanoa. Melko hankalaa tekstiä osittain. 

## Asennettujen ohjelmien lisenssit

Ensimmäisenä lähdin tutkimaan komentoriviohjelmaa Xeyes, jonka avulla saat silmät ruudulle, jotka seuraavat hiiresi liikettä. 
![Kuva 6 1](https://user-images.githubusercontent.com/100162043/214512030-751348c0-8d4b-4d22-b772-003a4934af4d.jpg)

 - Tästä löysin googlettamalla tiedot sivustolta https://pkgs.alpinelinux.org/package/edge/community/x86/xeyes ja tämän mukaan ohjelma käyttää MIT lisenssiä.
 - Kyseessä on vapaasti muokattava lisenssi 
 - Lisenssillä et voi tehdä kuitenkaan pitää koodin tekijää/tekijöitä laillisesti vastuussa mistään syystä. Et voi myöskään poistaa tekijänoikeusilmoitusta ja alkuperäistä lisenssiä koodiversiostasi. Lähde: https://fossa.com/blog/open-source-licenses-101-mit-license/ 
 - MIT ja BSD-lisenssi jätti pari kysymystä ilman, että lähdin tutkimaan asiaa sen tarkemmin. Nämä kyseiset lisenssit ovat erittäin samanakaltaiset ja sisältävät samat perusvaatimukset. BSD-lisenssissä on kuitenkin useita muunnelmia ja se sisältää kielen, joka on hieman vähemmän sallittu. 

Toisena ohjelmana lähdin tutkimaan komentoriviohjelmaa cmatrix, joka tuo elokuvasta tutun näkymän ruudullesi. 
![Kuva 5 1](https://user-images.githubusercontent.com/100162043/214517598-0b46db63-de93-4e8d-87d8-eb2add033a19.jpg)

 - Tästä löysin googlettamalla sivustolta https://archlinux.org/packages/community/x86_64/cmatrix/ ja tämän mukaan ohjelma käyttää GPL3 lisenssiä.
 - Kyseessä on GPL lisensseistä se eniten käyttörajoituksia sisältävä lisenssi. Lisenssi pyrkii vastaamaan muun muassa haasteisiin, joita ohjelmistopatentit asettavat vapaiden ohjelmistojen kehittämiselle. Lisenssin alla olevia ohjelmiin voi tehdä lisäyksiä tai suuria muutoksia ja jakaa sitä eteenpäin. Muokattuun varsioon pätee kuitenkin samat lisenssivaatimukset kuin alkuperäisessä. Lähde https://fossa.com/blog/open-source-software-licenses-101-gpl-v3/ 
 - GPL3 lisensoidun ohjelman muunnelman valmistaja menettää lisenssin tuomat oikeudet, mikäli hän uhkaa ohjelmiston käyttäjiä patentteihin liittyvin oikeustoimin. 
 - https://fossa.com/blog/open-source-software-licenses-101-gpl-v3/ antoi hyvin tietoa aiheeseen liittyen. 

Viimeisimpänä kyseenalaiseksi ladattu ohjelmisto 


    
 
