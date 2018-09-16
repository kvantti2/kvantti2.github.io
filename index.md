# Kvantitatiiviset tutkimusmenetelmät II/syksy 2018

Tee kaikki harjoitustehtävät ja palauta ne yhtenäisenä dokumenttina. Tehtävät perustuvat seuraavaan oppimisdataan ja tästä kirjoitettuihin julkaisuihin:

* [harjoitusdata](https://github.com/kvantti2/kvantti2.github.io/raw/master/data/harjoitusdata-korj.sav)
* Costello, A. B., & Osborne, J. W. (2005). Best practices in exploratory factor analysis: Four recommendations for getting the most from your analysis. Practical assessment, research & evaluation, 10(7), 1-9. ([pdf](https://www.pareonline.net/pdf/v10n7.pdf))
* Salmela-Aro, K., Kiuru, N., Leskinen, E., & Nurmi, J. E. (2009). School burnout inventory (SBI) reliability and validity. European journal of psychological assessment, 25(1), 48-57. ([pdf](https://www.researchgate.net/publication/232593343_School_Burnout_Inventory_SBI_Reliability_and_Validity))
* Salmela-Aro, K., & Upadaya, K. (2012). The schoolwork engagement inventory. European Journal of Psychological Assessment. ([pdf](https://github.com/kvantti2/kvantti2.github.io/raw/master/data/Salmela-Aro_Upadyaya_2012_EDA.pdf))
* Anna Varonen, Heta Tuominen, Lauri Hietajärvi, Katariina Salmela-Aro, Kai Hakkarainen & Kirsti Lonka (2018). Tavoiteorientaatiot, koulutustavoitteet ja koulumenestys kuudennella luokalla. Psykologia 53 (02-03) ([pdf](https://github.com/kvantti2/kvantti2.github.io/raw/master/data/Varonen_ym_Psykologia_2-3_2018.pdf))

## Arvostelu

- *hylätty* harjoitustehtäviä ei joko ole tehty, tai ne on tehty radikaalisti väärin ja/tai tulkittu erityisen väärin.
1. Kaikki harjoitustehtävät yritetty tehdä suurin piirtein oikein. Tulkinta vajavaista mutta oikean suuntaista, raportoinnissa (t.s. tulosten ja menetelmällisten valintojen aukikirjoittaminen) puutteita.
2. Kaikki harjoitustehtävät on tehty oikein. Tulkinta vajavaista mutta oikean suuntaista, raportoinnissa joitain puutteita.
3. Kaikki harjoitustehtävät on tehty oikein. Tulkinta oikean suuntaista ja raportoitu riittävästi, kirjallisuuteen viitataan.
4. Kaikki harjoitustehtävät on tehty oikein JA raportoitu siististi (esim. taulukot ei kopioitu suoraan SPSS-tulosteesta, vain keskeiset tunnusluvut, raportin asettelu helppolukuinen). Menetelmälliset valinnat on perusteltu asianmukaisesti suhteessa tutkimuskirjallisuuteen ja aineiston erityispiirteisiin. Tulkinta hyvin perusteltua ja kriittistä sekä hyvin raamitettu suhteessa kirjallisuuteen.
5. Kaikki harjoitustehtävät on tehty erinomaisesti JA raportoitu erityisen siististi (esim. APA:n ohjeiden mukaisesti). Menetelmälliset valinnat on perusteltu asianmukaisesti suhteessa tutkimuskirjallisuuteen ja aineiston erityispiirteisiin. Tulkinta erinomaista ja raamitettu laajasti suhteessa kirjallisuuteen.

## Tehtävät

### Korrelaatio

1. Pelaa guessthecorrelation.com kunnes kasassa on vähintään 30 pistettä. 
2. Piirrä seuraavat scatter-plotit:  
  - X = oppimisorientaatio, Y = keskiarvo
  - X = menestysorientaatio, Y = keskiarvo
  - X = suoritus-lähestymisorientaatio, Y = keskiarvo
  - X = suoritus-välttämisorientaatio, Y = keskiarvo
  - X = välttämisorientaatio, Y = keskiarvo
  Tulkitse eri tavoiteorientaatioiden yhteyttä kouluaineiden keskiarvoon kuvien perusteella.
3. Laske korrelaatiomatriisi sisältäen tavoiteorientaatiot ja kouluaineiden keskiarvon. Vertaile scatter-plotien ja Pearson korrelaatiokertoimien tarjoamaa informaatiota. Laske myös Spearman, eroavatko tulokset? Raportoi tulokset ja tulkinta.
4. Ota kantaa seuraaviin väitteisiin. Perustele kantasi. 
  - Jos testin A ja testin B välillä vallitsee korkea positiivinen korrelaatio, voidaan olettaa, että joko A on B:n syy tai B A:n syy
  - Korkea positiivinen korrelaatio antaa yhtä paljon informaatiota testattavien ilmiöiden välisestä yhteydestä kuin korkea negatiivinen korrelaatio.
  - Jos A:n ja B:n välinen korrelaatio on likimain nolla, ei A:n ja B:n välillä vallitse juuri minkäänlaista yhteyttä
5. Tutkija selvitti korrelatiivisesti oppilaan sosiaalisen taustan ja koulumenestyksen välistä yhteyttä. Tulokset olivat: tytöt (N=67) r=.36 ja pojat (N=132) r=.12. Kertoimista tutkija päätteli mm., että tytöt menestyivät koulussa paremmin kuin pojat. Miten itse tulkitsisit?

### Eksploratiivinen faktorianalyysi

1. Tee eksploratiivinen faktorianalyysi erikseen kouluinto- (EDA, Salmela-Aro & Upadyaya, 2012) ja koulu-uupumus-mittareille (SBI, Salmela-Aro, Kiuru, Leskinen & Nurmi, 2009). 
  - Arvioi mikä faktorimalli sopii parhaiten aineistoon ja miten se on suhteessa validointiartikkeleissa esitettyihin malleihin. Raportoi ja perustele valintasi faktorianalyysin suhteen (Costello & Osborne, 2005).
  - Miten vastaavien konfirmatoristen faktorianalyysimallien rakentaminen (ja lopputulos) eroaisivat näistä (ks. Salmela aro et al., 2009; 2012)? 

2. Tee valitsemasi faktorimallin mukaisesti keskiarvosummamuuttujat kuvaamaan faktoreita (käytä mean –funktiota). 
  - Tarkastele summamuuttujiesi jakaumia. 
  - Laske valitsemiesi faktorimallien mukaisten keskiarvosummamuuttujien reliabiliteettikertoimet (Cronbach’s Alpha) ja pohdi tulosta suhteessa alkuperäisiin osioihin/väittämiin ja faktoriratkaisuun.

### Varianssianalyysi

1. Artikkelissa “Tavoiteorientaatiot, koulutustavoitteet ja koulumenestys kuudennella luokalla” on esitelty neljä tavoiteorientaatioprofiilia. Profiilijäsenyydet kertova luokittelumuuttuja löytyy harjoitusaineistosta, samoin kuin profiilien estimoimiseen käytetyt tavoiteorientaatio-muuttujat. Taulukossa 2 on esitelty tavoiteorientaatioprofiilien keskiarvoerot tavoiteorientaatiomuuttujien suhteen (varianssianalyysi). Toista vastaava varianssianalyysi, tarkista, että saat yhtenevät tulokset. Raportoi tulokset. 
2. Vertaile tavoiteorientaatioprofiileja suhteessa tekemiisi kouluinnon ja koulu-uupumuksen keskiarvosummamuuttujiin. Tulkitse tulokset suhteessa aiempaan tutkimukseen (ks. lähteet). 
  * Tee sekä varianssianalyysi, että Kruskall-Wallisin u-testi. Vertaile tuloksia. Raportoi tulokset ja tulkinta.

### Regressioanalyysi 

Artikkelissa “Tavoiteorientaatiot, koulutustavoitteet ja koulumenestys kuudennella luokalla” (Varonen ym., 2018) on käytetty henkilösuuntautunutta tutkimustapaa ja vertailtu eri tavoiteorientaatioryhmiä koulutustavoitteiden arvioinnin ja koulumenestyksen suhteen. Valitaan nyt muuttujakeskeinen tutkimustapa samaan ilmiöön. Tutki lineaarisella regressioanalyysillä miten tavoiteorientaatiot ovat yhteydessä koulumenestykseen. Eroaako tulosten tulkinta eri lähestymistapojen välillä? Raportoi tulokset ja tulkinta.
