# delirium
very cool gaem

will be very kooler

Game Loop:
	update
	render




2DMap:

Gráf
	csúcs = mező
	van él = szomszédos
Generálás:
1.) P pontok elhelyezése
2.) minden (x, y) pont a síkon hozzátartozik a legközelebbi P ponthoz

Javaslat: legyen alatta mini hatszöges rács a sík




Terrain:
	terrain enum

Hatszög:
	HatszögPos(x, y)
	kihez tartozik

Province:
	buildingSlots: Int
	terrain: Enum
	neighbour: Province*
	...



