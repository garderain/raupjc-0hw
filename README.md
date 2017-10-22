# raupjc-0hw
#Pitanje 1:
U bin/Debug folderu se sada nalaze dvije nove datoteke od kojih je .dll ključna za izvođenje naše aplikacije jer je ona asemblij u kojem se nalazi metoda klase koju referenciramo u nasoj aplikaciji pa upravo zbog toga u nedostatku te datoteke naš .exe pada pa bi smo zbog toga morali poslati obje datoteke ako bismo nekome htjeli prosljediti našu aplikaciju.
#Pitanje 2:
Ako specificiramo da ne želimo nikakvu akciju nad ClassLibraryem prilikom buildanja i pokrenemo aplikaciju unutar VS-a dobit cemo error no VS ce nas pitati želimo li pokrenuti zadnji uspješan build te će samim time ispisati stari string jer se on nalazio u zadnjem compileu zadnjeg stabilnog builda. Također ako pokrenemo .exe on također ispisivati stari string jer se u njegovom .dll-u ništa nije promjenilo jer nije buildana nova verzija .dll-a. No ako samo pokrenemo aplikaciju unutar VS-a on će sam automatski buildati sve potrebno za izvođenje.
#Pitanje 3:
S build procesom se nije desilo ništa bitnije poput nekog errora ili slično već se tijekom build procesa se ponovno preuzeo direktorij za NodaTime u direktorij packages i sve se dalje odvijalo kao inače.
