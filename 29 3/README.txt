
LESING AV MASTER-FILE-TABLE:
1. En peker settes til starten paa et buffer, nemlig BUFFER
2. En offsett/jumper blir deklarert som hopper antall bytes som jeg oonsker aa lese for
en bestemt variabel.
3. Etter at jeg har lest inn alle variablene for en inode saa gjentar jeg dette i
form av en lokke.
4. Alle inoder blir lagret i et array som holder paa alle inodepekere.
5. Deretter looper jeg gjennom alle inodene og setter pekerne til hverandre
6. dette er ikke en fullstendig filsystem, men et system som fungerer greit :)
