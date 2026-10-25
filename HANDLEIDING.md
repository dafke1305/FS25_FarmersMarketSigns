# Farmers Market Signs — Handleiding

[Nederlands](HANDLEIDING.md) · [English](USER_GUIDE.md) · [Download / README](README.md)

Voor het pakket **1.0.0.0** uit [deze release](https://github.com/dafke1305/FS25_FarmersMarketSigns/releases/tag/v1.0.0.0). Deze instructies horen bij die ZIP, niet bij een andere build met hetzelfde versienummer.

## Installatie

1. Download **FS25_FarmersMarketSigns.zip** onder Assets van de release. Behoud de bestandsnaam en pak de ZIP niet uit. De automatische GitHub Source code-archieven zijn niet de mod.
2. Plaats de ZIP in de ingestelde FS25-modsmap (op Windows gewoonlijk `Documents\My Games\FarmingSimulator2025\mods`) en schakel de mod in vóór het laden van de savegame. Deze scriptmods zijn voor PC/Mac.
3. Server en alle multiplayerclients moeten **dezelfde ZIP** hebben, niet alleen hetzelfde versienummer. Sluit het spel/stop de server en maak vóór bijwerken een saveback-up.

## Een bord plaatsen en invullen

1. Open **Bouwen > Decoratie**. Kies het reclamebord, ingangsbord, A-bord, staande bord, totem of houten bord. Prijzen: 150, 450, 600, 750, 1.000 en 1.500; onderhoud: nul.
2. Plaats het bord voor je boerderij. Het maximum is **zes borden per boerderij over alle modellen samen**, niet zes van elk model.
3. Loop ernaartoe en gebruik **Reclamebord bewerken / Edit advertising board** in de contextuele F1-hulp. Je moet bij de eigenaarboerderij horen of in-game beheerder zijn.
4. Kies een van zes ontwerpen. Bewerk de **boventitel**, aparte **koptekst** en maximaal **vier product-/prijsregels**. Een lege productnaam verbergt de regel.
5. Titel/koptekst: maximaal 40 tekens; productnaam: 32; prijs/eenheid: 24. Een handmatige prijs zoals `EUR 250 / 1000 L` is alleen tekst: het bord rekent niets af en maakt geen handelstransactie.

Een ander ontwerp kiezen bewaart de teksten. Nachtverlichting aan beide kanten werkt automatisch.

## Boerderijlogo's

Gebruik **Boerderijlogo kiezen / Choose farm logo** voor een van elf ingebouwde logo's, of de standaard productafbeelding zonder logo. De keuze geldt voor **alle borden van die boerderij**. Ontwerp en tekst blijven per bord afzonderlijk.

Eigen DDS-logo's moeten eerst aan het gezamenlijke modpakket worden toegevoegd. Een lokale afbeelding selecteren uploadt die niet naar de server. Een aangepast pakket moet op server en alle clients identiek zijn.

## Optioneel Farmers' Market volgen

Zonder Farmers' Market kun je de borden handmatig gebruiken. Voor automatische aanbiedingen schakel je een compatibele **FS25_FarmersMarket** in, publiceer je aanbod voor de eigenaarboerderij en kies je **Productbron > Farmers Market automatisch volgen**.

De automatische stand toont maximaal vier gepubliceerde product-/prijscombinaties van die boerderij, met prijzen per 1.000 liter. Het bord leest aanbod: het maakt geen advertenties, wijzigt geen prijzen en verplaatst geen goederen. Handmatige regels blijven bewaard; schakel terug naar handmatig om ze te bewerken.

## Problemen oplossen

| Probleem | Controle |
| --- | --- |
| Geen extra bord te plaatsen | Tel alle zes modellen voor je boerderij samen. |
| Geen bewerkactie | Benader het bord te voet en controleer eigendom/beheerdersrechten. |
| Automatische regels blijven leeg | Controleer of de markt actief/gereed is en dezelfde boerderij gepubliceerd aanbod met voorraad heeft. Niet iedere andere marktbuild biedt de koppeling aan. |
| Meerdere borden krijgen een ander logo | Het logo is boerderijbreed; ontwerp en tekst blijven per bord apart. |

## Hulp vragen

Gebruik [het bug-/supportformulier van deze mod](https://github.com/dafke1305/FS25_FarmersMarketSigns/issues/new/choose). Vermeld release/ZIP, FS25- en mapversie, singleplayer/host/client/dedicated, stappen, tijdstip en het volledige clientbestand `log.txt`; bij een dedicated-serverprobleem ook `server.log` van dezelfde sessie. Voeg relevante screenshots/video toe. De pakketcontrolecode staat in [PUBLICATION.json](PUBLICATION.json). Verwijder wachtwoorden, tokens en privéverbindingsgegevens vóór openbaar plaatsen. Gebruik voor privébewijs alleen een goedgekeurd privékanaal.

Standaardtoetsen zijn aanpasbaar. De actuele F1-hulp en je instellingen onder Besturing zijn leidend.
