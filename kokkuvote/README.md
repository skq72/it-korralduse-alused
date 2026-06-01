# Kokkuvõte


## a) Mis on Git ja miks seda kasutatakse?
Git on kaasaegne ja hajutatud versioonihaldussüsteem, mida kasutatakse failide muudatuste jälgimiseks aja jooksul. Seda kasutatakse peamiselt tarkvaraarenduses, et mitu inimest saaksid töötada sama koodibaasiga ilma üksteise tööd üle kirjutamata. Git võimaldab igal ajal naasta failide varasemate versioonide juurde, mis hoiab ära andmete kaotamise.

## b) Mis vahe on commitil ja pushil?
Commit on muudatuste salvestamine sinu kohalikus arvutis või veebibrauseri sessioonis, mis loob uue punkti faili ajaloos. Push on käsk, mis saadab kõik need kohalikud salvestatud commitid üles serverisse, näiteks GitHubi platvormile. Seega commit teeb muudatuse kindlaks sinu jaoks, aga push teeb selle nähtavaks ja kättesaadavaks ka teistele.

## c) Miks on harud (branches) kasulikud?
Harud on kasulikud, sest need võimaldavad luua peamisest koodist eraldi koopia, kus saab arendada uusi funktsioone või katsetada ideid. See tagab, et peamine haru ehk "main" jääb alati stabiilseks ja töötavaks. Kui uus arendus eraldi harus on valmis ja testitud, saab selle ohutult põhikoodiga liita.

## d) Mis on Pull Request ja milleks seda vaja on?
Pull Request (PR) on viis teavitada tiimikaaslasi või õpetajat sellest, et oled oma harus töö lõpetanud ja soovid muudatusi peamisesse harusse üle kanda. PR-i käigus saavad teised koodi üle vaadata, kommenteerida ja teha parandusi enne lõplikku liitmist. See on hädavajalik tööriist koodi kvaliteedi kontrollimiseks ja meeskonnatööks.

## e) Mille poolest erineb Git kõigest muust (nt failide kopeerimisest USB-le)?
Erinevalt failide käsitsi kopeerimisest või USB-mälupulgale salvestamisest, ei tekita Git failidest segaseid duplikaate nagu "fail_v2_lõplik". Git salvestab ainult failide siseseid muudatusi ehk "diffe" ja hoiab ühte terviklikku ajalugu. Samuti võimaldab Git mitmel inimesel muuta sama faili samaaegselt ja liidab need muudatused automaatselt kokku, mis on USB-ga võimatu.

## f) Kuidas seostub Git projektijuhtimisega (Issues = ülesanded, Kanban = Projects)?
Git ja GitHub ei ole ainult koodi hoidmiseks, vaid toimivad ka projektijuhtimise platvormina. Issues võimaldab kirja panna vead, ideed ja tulevased ülesanded, määrata neile vastutajad ja sildid (Labels). Neid ülesandeid saab siduda Kanban-laudadega (GitHub Projects), mis annab visuaalse ülevaate sellest, mis faasis mingi ülesanne parajasti on (tegemata, töös, tehtud).

## g) Kas hakkaksid GitHubi edaspidi kasutama? Milleks?
Jah, ma plaanin GitHubi kindlasti ka edaspidi kasutada. See on suurepärane koht oma koolitööde ja isiklike programmeerimisprojektide hoiustamiseks. GitHub toimib ka kui IT-spetsialisti portfoolio, mida saab tulevikus tööle kandideerimisel tööandjale näidata.

## h) Mis oli selle töö juures kõige raskem ja kõige lihtsam?
Selle praktilise töö juures oli kõige lihtsam profiili seadistamine ja esmaste kaustade loomine GitHubi veebikeskkonnas. Kõige rohkem tähelepanu ja süvenemist nõudis harude (branches) loogika mõistmine ning Pull Requesti tegemine ilma konfliktideta. Samuti oli väljakutseks õige Markdowni vormistuse jälgimine kõikides failides, kuid see andis hea praktilise kogemuse.

