# F24B Programmering

## Første Semester

Her er mine kodeeksempler til undervisning på første semester af Multimediedesigneruddannelsen. Vi skal arbejde med HTML, CSS og lidt med JavaScript. 

Den vigtigste mappe er sikkert *boilerplate* - den bliver model for stort set alle projekter på 1. semester. Hvis du henter dette repository, så kan du:

* Kopiere mappen med boilerplaten
* Omdøbe den kopierede mappe til noget mere passende
* Derefter redigerer du filerne ad libitum
* Rediger evt. README.md - her kan du skrive, hvad dit projekt går ud på (og ja det her er skrevet i en README.md fil)

## Boilerplate

Filerne i boilerplaten er:

~~~~~~
├── css
│   └── css.css
├── images
│   └── README.md
├── index.html
└── js
    └── js.js
~~~~~~

### index.html : HTML

Serveren forventer, at der ligger en indexfil i rodmappen. Index-filen er din "forside". Filnavnet skal være index.htm. Når indexfilen er færdig, kan du hurtigt oprette lignende filer, fx ved at kopiere index.html.

### ./css/css.css : Stylesheet

Mappen ./css/ er beregnet til dine stylesheets. Du kan have et eller flere stylesheets alt efter hvor kompliceret dit design eller din webløsning er. 

### ./js/js.js : JavaScript

Boilerplaten linker desuden til et JavaScript, som ikke gør meget andet end at fortælle at det er der. På første semester får du en kort introduktion til JavaScript. Emnet foldes for alvor ud på andet semester. 

### ./images/

I mappen images kan du lægge dine billeder. Det er vigtigt at have en god struktur i filer og mapper. Et avanceret website kan består af hundredvis af filer, så det er en god ide at placere dine filer således, at du kan finde dem igen ...

### Mapper og filnavne må ikke indeholde mellemrum 

Husk altid, at dine filer ikke må have navne med mellemrum på en server. Måske virker sagerne på din egen computer; men på en server giver det omgående problemer.

* Ikke sådan: `billede af nogen blomster . png`
* Men derimod sådan: `billedeAfNogenBlomster.png` (CamelCase)

## Editor

Koden skal redigeres i en editor. I undervisnigen bruger vi generelt *Visual Studio Code*. 

* [Download Visual Studio Code her](https://code.visualstudio.com/)

Men hvis du foretrækker andre editorer, så står det dig frit for at bruge den editor som passer til dit kreative gemyt. Der findes et hav af editorer, fx:

* Vi
* Vim
* Nano
* Atom 
* Brackets
* Notepad++
* Gedit
* Bluefish
* Geany
* |: etc :|

Tekstbehandlingsprogrammer, som *Libre Office*, *Microsoft Word* og lignende programmer kan generelt ikke bruges til koderedigering (med mindre du ved hvad du gør, og selv da er det umådeligt bøvlet).

/ petj