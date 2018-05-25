# Sticky footerby Codeberry
## Balazs Bejczi
Az abszolút pozíció megoldás
A position tulajdonság változtatása az egyik mód arra, hogy a footert a lap aljára helyezd. Négy egyszerû lépésre lesz szükséged:
Csomagolj mindent (a footert is beleértve) egy divbe.
Célozd meg ezt a csomagolót (wrapper), és állítsd a minimális magasságát 100vh-ra, illetve alkalmazd rá a position: relative; szabályt.
Utána célozd meg a footert magát, és állítsd a pozícióját absolute-ra, majd mozgasd a wrapper aljára.
A wrappernek adj egy alsó paddinget, ez legyen egyenlõ a footer magasságával, hogy a tartalom ne csússzon be a footer alá.
Figyeld meg, hogy a footernek muszáj megadnod egy szélességet, miután megváltoztattad a pozíciójának alapértelmezett értékét, különben nem tölti ki a viewportot.
Ennek a megközelítésnek az egyetlen hibája, hogy pontosan tudnod kell a footer magasságát. Ez a legtöbb esetben nem nagy dolog, csak tudj róla, ha ezt a megoldást választod.
