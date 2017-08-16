# igang-med-github-soren-paepcke
## Hvordan laver man et repository på wi73-github?

1. Hvis man allerede er bruger på github, skal man logge ind. (Ellers, skal man oprette en bruger og logge ind med denne.)

2. For at kunne oprette et repository på wi73, skal man være medlem af *organisationen* først, så hvis du ikke er blevet medlem der, skal du tjekke din rts-365-mail. (Da alle elever er blevet inviteret af lærerne)

3. **Når** man er logget ind, kan man trykke på et + ved siden af ens profilbillede, og derefter *New Repository*, så kommer denne skærm frem.

![Screenshot af repository](https://lh3.googleusercontent.com/lKNPpDHtKlAJwdPaO_yCSlSvvjsSEcLeJrEwj3Frnp1Xx9B2521cAMRoW1PBxK__xYZ8fNQ5AiDj3hjuOy7Bbb-_GJBHXgVGMiwy5hgiAaRHbS8r0_0O7qbQMJ8YB-dLmRpD-eRIyBJ1qQd6ekZ4mEoUV0pH7jGHc2tr5F6fet0spiBBMnvPQXBfoJFjEdWN1FJNj2Z1Is4dKNCSIRnDGpeIGcSQcUQ_ys96mHd-i_fTA01ln4mr8KoMobVFwoLy-RuoEDFH-z_TAoABtBMSbE88tbm6wieZUzGJ6UwU0F7FS2gNwPk3Bq6Yb9KT4wYJTxOVNicFNjknfy4WOqIA7-xThIWHRQ_d17nvE0YUNR8AaAe9PEYxAoq8GP8bIajnGVUOczcigNcx02Dbr6SEfliJyKNfplby-qam3NCNPM_kZFUPrvQDG3BbLPbAUNZJ1Bg2EP2ZPE9WtfeHE2PQUB0unfpUYgShuscSXsw0mYDlTrqBYJZAiNzC2DqBvnNVkpBkXJN39PvqIZP6c8kkxOfvRxKZvXbrQ2GdLcx1PbaP56GrkZcdZL-hFjKWNfAebXHuKsy_8MOdEtZIZQzI8TzjIotnD9sZaqo9X2rqfpIO8Blm3hkgNJCMOrJgNa9fz24ZaVVwiq0po3Hho29DQvrnQxKCx7i4zNTnoTxmgnfktQ=w490-h619-no)

4. Når man så kan se hvor man vil gemme sit repository, er det vigtigt at man vælger den rigtige **"ejer"**, i det her tilfælde skulle mit repository ligge under *wi73a-praktisk-web*.

5. Giv dit repository et sigende navn, og ikke sådan noget som "gnu prut" eller "360 n0 sc0pe guide", medmindre det selvfølgelig er det dit repository handler om. :sunglasses:
Evt. tilføj en *beskrivelse*, for kort at fortælle hvad det handler om.


6. Dernæst vælger du om det skal være et privat eller offentligt repository, privat bestemmer du selv hvem der skal have adgang.

7. Husk at vælge *Initialize this repository with a README*, det er README filen jeg laver denne guide i f.eks.

8. Bagefter skal du vælge *Add .gitignore* og sætte den til **Node**. 

9. Licens behøver du ikke gøre noget ved.

10. Tillykke ! :smile: 
Du har nu oprettet et repository, på [GitHub](http://github.com), og er godt på vej til at blive en superstar! *Keep on rockin'!*

### Tips & Tricks til tekst formatering

Man kan lave meget *forskellig* tekst formattering i GitHub's readme-filer.

#### Billeder
For at sætte et billede ind, skal man skrive:

```
![*Derp*](http://img2.wikia.nocookie.net/__cb20110608183440/inciclopedia/images/c/c8/Derp1.jpg)
```
![*Derp*](http://img2.wikia.nocookie.net/__cb20110608183440/inciclopedia/images/c/c8/Derp1.jpg)

#### Links

Sådan ser koden til links ud, i README:
```
Link til "Markdown" tips & tricks!
[Åbner en GitHub guide](http://github.com) 
```

Sådan her ser det ud med markdown:

Link til "Markdown" tips & tricks!
[Åbner en GitHub guide](http://github.com)

#### Markdown

Markdown er tekstformatteringen, på denne readme f.eks.

Det kan også bruges i kommentarer under "Issues", og "Pull Requests".

Du kan også vise kodestumper, vha. markdown.

```javascript
var betingelse = true;

if (betingelse = true){
    console.log("Hvis betingelsen er sand, denne kode bliver kørt")
}
else{
    console.log("Hvis betingelsen IKKE er sand, kører denne kode");
}
```