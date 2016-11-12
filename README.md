# UE4-Style-Guide-Deutsch-(WiP)
This is the translated German Version of the Style Guide from [Allar](https://github.com/Allar/ue4-style-guide)

# [Gamemakin](https://gamemak.in) UE4 Style Guide() {

*Ein durchdachter Ansatz für Unreal Engine 4*

Nach einer Vorlage des [Airbnb Javascript Style Guide](https://github.com/airbnb/javascript).



## Verlinken dieses Dokuments

Jeder Abschnitt dieser Stilleitfaden ist sowohl für einfache Referenz und einfache Verknüpfung nummeriert. Du kannst jeden Abschnitt direkt verlinken, durch einfaches Hinzufügen eines Hash-Tag und die Abschnittsnummer an das Ende von http://ue4.style
Zum Beispiel, wenn Du einen Link zum ersten abschnitt dieses Dokuments führen möchtest, wäre der richtige Link nach hinzufügen der #0.1 - http://ue4.style#0.1.

## Forks And Translations

If you have made a notable fork or translation that is not suitable for a pull request into this repo, please submit a pull request to add the fork or translation here. 
Ich habe keine Idee, was genau damit gemeint ist?! (Anm.d.Übersetzers!)

* [Koreanische Version](https://github.com/ymkim50/ue4-style-guide/blob/master/README_Kor.md) by ymkim50
* [Englische Version](https://github.com/Allar/ue4-style-guide) by Allar 

## Wichtige Terminologie

<a name="terms-level-map"></a>
##### Levels/Maps

Das Wort "Map" bezieht sich allgemein auf das, was man üblicherweise ein "Level" nennt. Lese dazu Das Wiki dieses Begriffs [hier] (https://de.wikipedia.org/wiki/Level_(Spielabschnitt) )
<a name="terms-cases"></a>
##### Cases

Es gibt verschidene Möglichkeiten der Bezeichnung. Hier einige Beispiele der Casing-Typen:

> ###### PascalCase
>
> Großbuchstaben bei jedem Wort und lösche die Zwischenräume, z.B.: `DesertEagle`, `StyleGuide`, `EineReiheVonWörtern`.
> 
> ###### camelCase
>
> Der erste Buchstabe klein und bei folgenden Wörtern groß geschrieben, z.B.: `desertEagle`, `styleGuide`, `aSeriesOfWords`.
>
> ###### Snake_case
>
> Wörter können mit Klein- oder Großbuchstaben beginnen, werden aber mit Unterstrich getrennt, z.B.: `desert_Eagle`, `Style_Guide`, `a_Series_of_Words`.


<a name="0"></a>
## 0. Grundlagen

Die Grundlagen wurden übernommen aus [idomatic.js style guide](https://github.com/rwaldron/idiomatic.js/).

<a name="0.1"></a>
### 0.1 Sollte Dein UE4 Projekt bereits einen StyleGuide haben, behalte diesen bei.

Wenn Du an einem Projekt oder mit einem Team arbeitest, welches bereits einen StyleGuide besitzt, sollte er vorrangig Beachtung finden. Bei Überschneidungen zwischen dem vorhandenen StyleGuide und diesem hier, sollte der vorhandene vorgezogen werden.

StyleGuides sind sich verändernde Dokumente und Du solltest Änderungen an einem bestheenden StyleGuide vorschlagen, so wie diesen hier, wenn sich dadurch Arbeitsweisen vorteilhaft verbessern würden.

> #### "Diskussionen über den Arbeitsstil sind sinnlos. Es sollte aber einen SyleGuide geben, dem man folgt."
> [_frei nach Rebecca Murphey_](https://rmurphey.com)
