# tanulas
full stack tanulás
## Alapvetések
Az alapvetések célja, hogy egyértelmű alapokat biztosítson eldönteni, hogy hol állunk, merre megyünk, mit célzunk és mit nem a munkánkkal.

- Olyan technológiát használunk, amit jelenleg programozóként a profik használnak és még jó darabig fejlődőképes marad (dotnet core).
- Olyan eszközöket használunk, amit a profi programozók is használnak.
- Olyan feladatot választunk, amit nem kell terveznünk, már létezik és körbejárható
- A tervet úgy készítjük, hogy később továbbfejleszthető legyen
## Vázlat
Vázlatunk célja megnevezni az egymásra épülő alkalmazásainkat és megrajzolni az összefüggéseket.

- elsődleges cél: egy webalkalmazás készítése (MVC)
- továbbfejlesztés: az adatok szolgáltatása és az üzleti logika elérése webapin keresztül (MVC)
- továbbfejlesztés: desktop alkalmazás készítése a webapira alapozva (WPF)
- mobil alkalmazás készítése a webapira alapozva (Xamarin)
- továbbfejlesztés: SPA: Single Page Application készítése a webapira alapozva (Blazor)
## Webalkalmazás
Készítsünk egy (továbbfejleszthető) oktató alkalmazást, ahova

- oktatók tudnak tanfolyamokat feltölteni, valamint
- hallgatók tudnak ilyen tanfolyamokat elvégezni
Ez egy jól áttekinthető, mégis kellően összetett feladat, ahol a full-stack C# fejlesztés minden részébe bepillanthatunk, immár a profi fejlesztő szemével.

## Objektumorientált tervezési gondolatok (OOD)
Csatolás (Coupling): ha egy elem függ más elemektől, akkor ezek az elemek csatolásban vannak.
gyenge (Low) ez a csatolás abban az esetben, ha a csatolásban lévő elemek esetén egy változás továbbterjedése megállítható.
Első célunk tehát: a gyenge csatolás (Low Coupling) elérése a dobozaink között.

Kohézió (Cohesion): Egy elem felelősségeinek egymáshoz való kapcsolata.
a kohézió gyenge (low), ha az adott elemnek túl sok egymástól független felelőssége van.
a kohézió erős (high), ha az adott elem felelősségei erősen összefüggnek és nagyon koncentráltak.
Célunk tehát az Erős kohézió (High Cohesion) elérése a dobozokon belül.

Költségek (vajon megéri?)
Függ a rendelkezésre álló erőforrás mértékétől.
Függ a rendelkezésre álló időtől is.
És leginkább az alkalmazás élettartamától függ.