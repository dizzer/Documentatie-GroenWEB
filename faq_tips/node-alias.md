http://zandhove.groen2.ys.be/admin/config/search/path
e website verandert inderdaad alle berichten in een alias, dat is de bedoeling. Standaard (en in de database) geeft drupal aan een bericht enkel een ID-nr: http://zandhove.groen2.ys.be/voorbereiding_gemeenteraad is hetzelfde als http://zandhove.groen2.ys.be/node/63. Voor de leesbaarheid van de gebruiker en SEO wordt dat nummer omgezet in

http://zandhove.groen2.ys.be/[titel_met_underscores]     voor gewone berichten en pagina's
http://zandhove.groen2.ys.be/onze_mensen/[titel_met_underscores]     voor medewerkers
http://zandhove.groen2.ys.be/dossier/[titel_met_underscores]  voor dossiers
http://zandhove.groen2.ys.be/[taxonomie]/[tag]  voor tags
http://zandhove.groen2.ys.be/users/[username]  voor gebruikers

Dus om een naam zoals 's61' te krijgen moet je dat als titel invoeren.

Voor bestanden en beelden die je oplaadt doet de naam er eigenlijk niet toe, op voorwaarde dat de website bijhoudt waar ze terechtkomen. Tijdens het opladen worden spaties vervangen door underscores, de karakters omgezet naar US-ASCII en grote letters naar kleine. Voor de eindgebruiker is het enkel van belang dat je bij het toevoegen van een beeld aan een bericht de titel en alt velden invult.
