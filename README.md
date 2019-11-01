# LED-keppihevoset micro:bitillä
LED-keppihevoset micro:bitillä - LED micro:bit hobbyhorse

<p>Testasimme Anjalan leirikeskuksessa elokuun lopussa uutta työpajaa, jossa keppihevosia tuunattiin rakentamalla niille kiiluvat LED-silmät ja ohjelmoimalla niitä micro:bit -mikrokontrollerilla. Tässä temppu, ja miten se tehtiin.</p>

<p>Uutinen Anjalan keppihevospajasta on luettavissa <a href="https://www.verke.org/news/nuorisokeskus-anjalassa-tuunattiin-keppareita-digiaikaan/">täällä.</a> Koska teknologinen värkkäily jää usein omaksi saarekkeekseen, eikä aina ole helppoa perustella miksi kyse on nuorisotyöstä, yhdistimme tässä työpajassa värkkäilyn olemassaolevaan nuorisotyölliseen toimintaan (kädentaidot) sekä nuorisokulttuuriseen ilmiöön (keppihevoset).</p>

<p>Ja se <strong>pakollinen vastuulauseke</strong>: Tämä ohje on täysin amatöörin kirjoittama ja olen pähkinyt itsekseni, kuinka tämä projekti toteutetaan. Vaikka tälläinen rakentelu ei ole erityisen vaarallista hengelle tahi ympäristölle, kannattaa käyttää esimerkiksi suojalaseja juottaessa ja muistaa, että kolvi on kuuma. Olen kokeillut. :) Verke ei ota vastuuta mahdollisista pienistä palovammoista, tinatuista pöydänkansista tai etenkään ylettömästä ja kasvavasta innostuksesta teknologiseen puuhasteluun.</p>

<p>Siispä eteenpäin!</p>

<h2>Tarvikkeet</h2>

<p>Tämä projekti toteutettiin kutakuinkin allaolevilla tykötarpeilla. Pihtien tarkka merkki, tinan ostopaikka tai johdon paksuus eivät ole tässä ne kaikkein olennaisimmat asiat, vaan samaan lopputulokseen voi päästä myös hyvin erilaisilla välineillä.</p>

<p><a href="https://www.verke.org/wp-content/uploads/2018/09/P1004356-Edit.jpg">
  <img class="wp-image-151988 size-material-image" src="https://www.verke.org/wp-content/uploads/2018/09/P1004356-520x371.jpg" alt="" width="520" height="371" /></a>
  
  LED -kepparin rakentamiseen käytettäviä tarvikkeita. Osat listattuna kuvaa klikkaamalla.</p>

<ul>
     <li>Keppihevonen. Joko kaupasta ostettu tai omavalmiste; huomioi kuitenkin, että kepparille joutuu suorittamaan "ruumiinavauksen" jotta elektroniikan saa asennettua.</li>
     <li><a href="https://kauppa.ilonait.fi/web/kauppa/bbc-microbit-go/">Micro:bit -mikrokontrolleri</a>. Käytetään LEDien ohjaamiseen ja käyttäytymisen ohjelmointiin.</li>
     <li><a href="https://www.partco.fi/fi/kaapelitjohdot/yksisaeikeiset-kytkentaejohdot/14316-kaa-kj-1x06-pun.html">Kytkentäjohtoa</a> , kahta eri väriä, kolme pätkää</li>
     <li>2 kpl <a href="http://www.kouluelektroniikka.fi/cgi-bin/shop.cgi?action=prodshow&amp;usr=6rofn773r4rsrlrlke0hp0pes0&amp;prodid=3413%20522">LED -valoja</a></li>
     <li>Kutistemuovia (valinnainen) tai sähköteippiä</li>
     <li><a href="http://www.bebek.fi/kauppa/lisatiedot.php?&amp;tuote_id=17721">Hauenleukajohto </a></li>
     <li><a href="http://www.kouluelektroniikka.fi/cgi-bin/shop.cgi?action=prodshow&amp;usr=6rofn773r4rsrlrlke0hp0pes0&amp;prodid=7002%20000">Kuorintapihdit</a></li>
     <li>Juotostinaa</li>
     <li>Kolvi tai juotosasema</li>
     <li><a href="http://www.bebek.fi/kauppa/lisatiedot.php?&amp;tuote_id=17530">Apukädet</a> (myös vakaakätinen kollega tai nuori käy)</li>
     <li><a href="http://www.kouluelektroniikka.fi/cgi-bin/shop.cgi?action=prodshow&amp;usr=6rofn773r4rsrlrlke0hp0pes0&amp;prodid=7117%20400">Kuumaliimapistooli</a> ja kuumaliimaa</li>
     <li>Suojalasit</li>
</ul>

<p>Lisäksi muita sekalaisia tarvikkeita kuten neula ja lankaa keppihevosen kasaan kursimiseen operaation jälkeen .</p>

<h2>Valmistelu</h2>

<p>Laita kolvi valmiiksi lämpenemään.</p>

<p><a href="https://www.verke.org/wp-content/uploads/2018/09/P1004357.jpg"><img class="alignleft wp-image-152001 size-medium" src="https://www.verke.org/wp-content/uploads/2018/09/P1004357-300x169.jpg" alt="" width="300" height="169" /></a> 
  
Leikkaa kytkentäjohto sopiviksi pätkiksi. Mitta on sopiva, kun kaksi pätkää + puolikas hauenleukajohto riittää suunnilleen kattamaan matkan micro:bitin ja patterikotelon sijoituspaikasta kepparin silmiin asti. Jätä johtoihin myös hieman varaa; ylimääräinen johto jää joka tapauksessa piiloon kepparin sisälle.</p>

<p><a href="https://www.verke.org/wp-content/uploads/2018/09/P1004358.jpg"><img class="size-medium wp-image-152002 alignleft" src="https://www.verke.org/wp-content/uploads/2018/09/P1004358-300x169.jpg" alt="" width="300" height="169" /></a>
  
Leikkaa hauenleukajohto puoliksi puolestavälistä. Hommaa selkeyttää, jos käytät puolikasta kahdesta eri johdosta jolloin saat kaksi eri väristä pätkää.</p>

<p>Kuori kaikki johtojen päät. Noin 5mm kuorittua johtoa riittää.</p>

<div class="mceTemp"></div>

<h2>Johtojen ja ledien juottaminen</h2>

<p><a href="https://www.verke.org/wp-content/uploads/2018/09/P1004538.jpg"><img class="alignleft size-medium wp-image-152004" src="https://www.verke.org/wp-content/uploads/2018/09/P1004538-300x169.jpg" alt="" width="300" height="169" /></a>
  
Laita johdot apukäsiin vierekkäin siten, että kuoritut päät ovat limittäin. Tarkoitus on juottaa nämä yhteen sulattamalla tinaa niiden väliin. Tinaa voi ajatella ikäänkuin sähköäjohtavana liimana; sen lisäksi että virta kulkee juotoksesta läpi, tina muodostaa myös mekaanisen liitoksen, eli johdot eivät irtoa toisistaan. Jos aiot käyttää kutistesukkaa liitosten suojaamiseen, pujota se johtoon tässä vaiheessa.</p>

<p>Jotta liitoksesta tulee hyvä, älä sulata kolvilla tinaa johtoon vaan lämmitä johtoja alapuolelta ja kosketa tinalangalla johtoja. Tällöin tinaa sulaa johtoihin eikä kolvin kärkeen. Apukädet auttavat tässä paljon, mutta työpajassa tuli testattua myös että tästä saa hyvin ryhmätoimintaa: toinen voi lämmittää johtoja kolvilla ja toinen syöttää tinaa liitokseen. Tietysti tässä mennään samalla hieman luottamusharjoituksen puolelle, mutta sekään ei välttämättä ole huono asia.</p>

<p><a href="https://www.verke.org/wp-content/uploads/2018/09/P1004361.jpg"><img class="alignleft size-medium wp-image-152003" src="https://www.verke.org/wp-content/uploads/2018/09/P1004361-300x169.jpg" alt="" width="300" height="169" /></a><a href="https://www.verke.org/wp-content/uploads/2018/09/P1004382.jpg"><img class="alignleft size-medium wp-image-152006" src="https://www.verke.org/wp-content/uploads/2018/09/P1004382-300x169.jpg" alt="" width="300" height="169" /></a>
  
Toista toimenpide kaikille johdoille; kolvaa hauenleualla varustettu johto yhteen päähän asennusjohdon pätkää ja toiseen päähän kaksi asennusjohdon pätkää lisää. Tavoitteena on Y:n muotoinen hässäkkä, jonka alaspäin osoittavassa kärjessä on hauenleukaliitin.</p>

<p><a href="https://www.verke.org/wp-content/uploads/2018/09/P1004452.jpg"><img class="alignleft size-medium wp-image-152005" src="https://www.verke.org/wp-content/uploads/2018/09/P1004452-300x169.jpg" alt="" width="300" height="169" /></a>
  
 Kun olet kolvannut johdot kasaan, on aika liittää LEDit ketjuun. Laita yksi LEDeistä apukäsiin ja toiselle puolelle toinen tekemistäsi Y-johdoista. Valitse, kumpi johdoistasi on + ja kumpi - ja valitse ensimmäiseksi positiivinen johto. Ledien toinen jalka on aina hieman pidempi, tämä on + -jalka. Juota + johdon toinen vapaa pää ensimmäisen LEDin pidempään jalkaan. Vaihda tilalle toinen LED ja juota toinen + johto pidempään jalkaan. Sen jälkeen vaihda hauenleukoihin toinen Y-johdoistasi - aivan oikein, se miinusmerkkinen! - ja toista sama molempien LEDien lyhyemmille jaloille.</p>

<p><a href="https://www.verke.org/wp-content/uploads/2018/09/P1004562.jpg"><img class="size-medium wp-image-152008 alignleft" src="https://www.verke.org/wp-content/uploads/2018/09/P1004562-300x169.jpg" alt="" width="300" height="169" /></a></p>

<p>Testaa kytkentöjen toimivuus esimerkiksi kytkemällä nappiparisto virtapiiriin; yksinkertaisesti kosketa hauenleukojen toista puolta pariston positiiviseen napaan ja toista negatiiviseen. LEDien pitäisi syttyä. Huraa!</p>

<p>Mikäli valoa ei kansalle tule, on pari vaihtoehtoa: joko johtosi ovat väärin päin (käännä patteri) tai kytkennöissäsi on virhe. Tarkista kytkennät ja korjaa tarvittaessa; tina on helppo sulattaa johdoista pois.</p>

<h2>Micro:bitin kytkentä ja ohjelmointi</h2>

<p>Nyt kun tiedät, että LED -virtapiiri toimii, on aika hypätä ohjelmoinnin kimppuun.</p>

<p>Micro:bit -ohjelmointialustan peruskäyttöön on paljon myös suomenkielistä materiaalia, joten en ohjeista tässä aivan perusasioita. Erinomainen resurssi on esimerkiksi <a href="https://www.innokas.fi/materiaalit/?_sft_material_type=microbit">Innokas -verkoston materiaalipankki.</a> Käy lukaisemassa selkeä <a href="https://www.innokas.fi/wp-content/uploads/2017/08/01_Microbit_kayttoohje-1.pdf">perusohje</a> ja tule takaisin.</p>

<p>Hyvä, miltä näytti? Ohjelmoitpa micro:bittiäsi sitten tietokoneella tai mobiililaitteella, perusidea on sama: laite ajaa kerrallaan vain yhtä koodia, heti ja välittömästi kun micro:bit laitetaan päälle (yleensä kytkemällä paristokotelon johto kiinni laitteeseen).</p>

<p><span style="color: black;">Itse en ole kummoinen koodari, mutta micro:bitissä käytettävä visuaalinen ohjelmointiympäristö on onneksi erittäin helppo käyttää. Pohdittavaksi jääkin lähinnä se, mitä haluan saada laitteen tekemään. Mietitäänpä hetki:</span></p>

<ul>
     <li><span style="color: black;">Haluan, että <strong>kun</strong> micro:bittiä ravistetaan, <strong>tapahtuu</strong> jotain (esimerkiksi <strong>LED-</strong><strong>valot vilkkuvat</strong>)</span></li>
</ul>

<p>Ylläoleva lause on itseasiassa jo ohjelmointia; käytännössä lähestulkoon kaikki ohjelmointi perustuu yksinkertaistetusti logiikkaan "kun tapahtuu asia x, tee asia y". Vaikka "asia y" on joskus melko monimutkainen kokonaisuus, tässä päästään vielä onneksi melko helpolla.</p>

<p>Mene osoitteeseen <a href="http://makecode.microbit.org">makecode.microbit.org</a> ja tutkaile hetki ohjelmointimpäristöä. Voit halutessasi vaihtaa kielen suomaksi klikkaamalla rattaan kuvaa.</p>

<p>Koodaamaan! Ohjelmamme kuuluu siis näin: <strong>kun</strong> microbittiä <strong>ravistetaan</strong>, vilkuta <strong>led-valoja.</strong> Otetaan pala kerrallaan:</p>

<p><strong>1</strong> Ota "syöte" välilehdeltä - kyllä, arvasit oikein - ehtolause "<strong>Kun ravistetaan</strong>" ja raahaa se koodialustalle.</p>

<p><strong>2</strong> Koska haluamme ohjata ulkoisia LED -valoja, <strong>älä</strong> valitse välilehteä "LED" vaan klikkaa edistyneet ja etsi välilehti "Pinnit". Sieltä löydät "<strong>Digitaalinen kirjoittaminen pin [p0] arvoon [0]"</strong>. Raahaa tämä koodinpala edellisen kohdan toistolauseen sisään. "Koodinpalat" lukittuvat yhteen kun laitat ne oikeaan kohtaan.</p>

<p><em>Tässä kohtaa on hyvä todeta, että "pin 0" vastaa tässä micro:bitin alareunassa olevaa kullanväristä liitintä. Liittimiä on useita, mutta toinen johdoistamme tullaan kytkemään reunimmaiseen "gnd" pinniin ja toisen voit valita itse. Pin 0 on ehkä helpoin jotta johdot eivät ole aivan vierekkäin. </em></p>

<p><em>"Digitaalinen kirjoittaminen" tarkoittaa tässä sitä, että jokainen pinni on joko päällä tai pois. Arvo 1 on tietenkin päällä ja arvo 0 tarkoittaa että pinniin ei lähetetä signaalia.</em></p>

<p><strong>3</strong> Koska haluamme sytyttää valot kun micro:bittiä / kepparia ravistetaan, vaihda digitaalinen kirjoittaminen -koodinpätkästä <strong>arvoksi "1"</strong></p>

<p><strong>4 </strong>Koska haluamme myös sammuttaa valot, kopioi "Digitaalinen kirjoittaminen" -koodinpätkä ja vaihda arvoksi <strong>0</strong>.</p>

<p><strong>5 </strong>Koska micro:bit on pienestä koostaan huolimatta melko hätäinen kaveri ja vilkuttaa valoja niin nopeasti kuin pystyy, kannattaa väliin lisätä pieni tauko. Ota siis yleiset -välilehdeltä sininen palikka "tauko" ja lisää haluamasi mittainen tauko (sekunnin sadasosina, 100ms on siis yksi sekunti).</p>

<p><a href="https://www.verke.org/wp-content/uploads/2018/09/whenshake.png"><img class="alignleft size-medium wp-image-152022" src="https://www.verke.org/wp-content/uploads/2018/09/whenshake-300x113.png" alt="" width="300" height="113" /></a>
  
Vaikka koodin pitäisi periaatteessa toimia jo tälläisenään, halusin vielä hienosäätää sitä hieman. Siispä lisäsin silmukat -välilehdeltä lausekkeen "toista x kertaa", jotta sain valot vilkkumaan kuusi kertaa jokaisen ravistuksen jälkeen.</p>

<p>Tallenna koodi micro:bittiin ohjeiden mukaan, joko siirtämällä se usb -kaapelilla tietokoneelta tai bluetooth -yhteydellä puhelimelta. <strong>Toim. huom: </strong>Verken micro:bit -yksilöt eivät halunneet siirtää koodia ainakaan allekirjoittaneen puhelimesta, ennenkuin micro:bitin laittoi joka kerta uudelleen paritustilaan koodin siirron ajaksi. Uutta paritusta ei siis tarvitse tehdä, vaan riittää kun micro:bitin laittaa paritustilaan ennen koodin siirtoa.</p>

<h2>Testaus ja asennus</h2>

<p>Kytke rakentamasi LED -hässäkkä hauenleuoilla micro:bittiin. Huomaa, että leuat eivät saa osua viereisiin kultaisiin pinneihin, muuten tuloksena on oikosulku, josta ei onneksi ole suurempaa haittaa kuin virtapiirin hetkellinen toimimattomuus. Kytke positiivinen johtosi pinniin 0 (tai minkä määrittelitkään ohjelmointivaiheessa) ja miinusjohto gnd -merkittyyn pinniin (maa). Nyt kun kytket virtajohdon micro:bittiin, valojen pitäisi vilkkua!</p>

<p>Jos mitään ei kuitenkaan tapahdu, tarkista seuraavat: ovatko johtosi oikein päin? Ovatko kytkentäsi edelleen ehjät? Onko koodissasi jotain vikaa, kenties huolimattomuusvirhe jossain? Vianetsintä on joskus turhauttavaa, mutta toisaalta monesti myös erittäin palkitsevaa.</p>

<p><a href="https://www.verke.org/wp-content/uploads/2018/09/IMG_20180903_143138.jpg"><img class="alignleft size-medium wp-image-152025" src="https://www.verke.org/wp-content/uploads/2018/09/IMG_20180903_143138-150x300.jpg" alt="" width="150" height="300" /></a><img class="alignleft size-medium wp-image-152023" src="https://www.verke.org/wp-content/uploads/2018/09/IMG_20180903_150217-150x300.jpg" alt="" width="150" height="300" /> <a href="https://www.verke.org/wp-content/uploads/2018/09/IMG_20180903_150200.jpg"><img class="alignleft size-medium wp-image-152024" src="https://www.verke.org/wp-content/uploads/2018/09/IMG_20180903_150200-150x300.jpg" alt="" width="150" height="300" /></a> 
  
  Kun toteat, että kaikki toimii ja micro:bit ohjaa ledejä haluamallasi tavalla, voit asentaa LEDit ja johdot pysyvästi paikoilleen keppariin. Taiteellinen ja luova vapaus on sinulla, mutta itse toteutin asennuksen siten, että pujotin johdot LEDeineen kepparin pään sisälle ja otin LEDit silmien paikoista ulos. Sitten laitoin LEDit pieniin pahvinpaloihin kiinni ja liimasin pahvinpalat kuumaliimalla paikoilleen. Hauenleukapäät johdoista ja micro:bitin paristokoteloineen  jätin ulkopuolelle siten, että saan tarvittaessa micro:bitin helposti irroitettua.</p>

<p><a href="https://www.verke.org/wp-content/uploads/2018/09/IMG_20180903_150211.jpg"><img class="alignleft size-medium wp-image-152026" src="https://www.verke.org/wp-content/uploads/2018/09/IMG_20180903_150211-300x300.jpg" alt="" width="300" height="300" /></a></p>

<p>&nbsp;</p>


