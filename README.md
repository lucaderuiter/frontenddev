# frontenddev


 22/09
 FED herkansing
Het idee is om de site opnieuw op te bouwen en de fouten eruit te halen. We hebben gekeken naar de feedback van Laura en hoe ik een iteratief proces ga lieten zien. 
> Kijken naar de structuur van de site
> 3 feedbackrondes voor deze website
> opdracht dit jaar: 
- > procesronde en verslag (Hoe gaan wij dit doen?)
> feedback uitwisselen

> Laat een iteratief proces zien. 

> week 10 inlevermoment

> eerste feedback moment afspreken, op GitHub inleveren. 

CODE:
home
Een uitgebreide head: 
> kijk naar het template op DLO en overnemen wat daar staat
> id = voor java inderdaad
> classes voor img niet heel netjes
> article moet met pseudo-element
> main article:first-child voor de intro
> tweede br, maak er twee paragrafen van. 
> headers in list , h2 weghalen, en er een p van maken. 
> article:nth-of-type(2) li {} < zo kan jet het tweede type aanroepen.
> eventueel een span gebruiken
> met css oplossen de br bij de footer
> ipv p een label

> script moet boven je body. 

categorie: 
!deze gana we verwijderen!

Detail: 
> haal de br weg. 
>"sectionmidlinks" etc classes moeten anders - naar flexbox toe. 

CSS
> position relative and absolute
> fallback font, sans-serif erachter
> of een font importeren? - werkgroep typografie
> roep beide tegelijkertijd aan - li:hover, nav a:hover {}
> body: font defineeren bij de body  
> Constitent font gebruiken! 
> font-size 1 em, dan overal em!
> Centreer teksten waar dit nodig is
> orangeslice is goed, naam nog even veranderen? 
> veel hardcode pixel waardes, wat niet heel netjes is (liever geen pixels dit schaalt ook moeilijker mee) 
> De tekst bij de img  - over deze as, verticaal willen we het centreren, "center rotated". Hoe ga dit doen? transform (translate) 
> z-indez niet nodig bij sommige - of trek het gelijk.
> mainarticle, centreren van elementen 
> Veel herhaling bij de code dat niet nodig is. 

mediaqueri
- Hier dingen veranderen en weghalen en dan gaan ze eerst kapot, om vervolgens weer goed op te bouwen. 
- grote absolute waardes weghalen, random heights en width overal, maak er vh of vw van, dit schaalt. wat doet er raar en wat niet? 

Opschonen en structuur maken en dan hebben we de volgende afspraak: 2 oktober.
github en dlo online op 2 oktober
notes in the readme


06/10
> <span></span> voor stijlen
> kleine n
> h3 allebei in detail 
> liever em dan px 
> margin: constituent em gebruiken dan schaalt alles mee

> nav li, geen hover - gebruik een transition!

> Gberuik vh en vw!

> op borders wel px

> form liever em 

> a href=‘#’ - om er doorheen te kunnen tabben.

> doorheen tabben met een a

> padding consistent om tekst gebruik em!

> submit heeft ook een transitie nodig

———
15/10

> orange.nth of type - gebruik dit. 
> class mag je behouden

> in css bestand, verschillende dingen aanspreken

> alle images bij elkaar in een class

> classes wegwerken + sectionmidrechts etc weghalen. 
———

> padding in em!!! 

> z-index gelijk trekken! altijd -1
———

> hover naar img toe - geen hover, maar transition
——

> haal dit weg (sectionmidregels) and maak er nieuwe regels van, schrijf het opnieuw. 

> tabindex bij de buttons. of maak er buttons van. 

——
>zet READ ME erin notities

> Formulier nog netjes maken en mee laten schalen. 
———
—
aanpassen voor tablet en desktop!!!

Inlevern 28 oktober en om 12 uur het gesprek

