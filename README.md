# TV-spelsdatabas

I denna uppgift så ska ni skapa en databas som lagrar data om tv-spel, genre och konsoler. Som krav på funktionalitet så får in några user stories som ni ska följa.

1. Som samlare vill jag ha ett register på spel där jag kan se deras namn och genre.

2. Som samlare vill jag kunna se vilka spel som tillhör en viss konsol

3. Som samlare vill jag kunna se vilka spel som tillhör en viss genre.

Man ska alltså kunna ställa frågor till databasen som kopplar ihop spel med en viss genre samt konsol. Databasen ska vara **normaliserad**, _( minst första normalformen uppfylld )_ vilket här i praktiken innebär att en tabell med ett spel inte får innehålla konsollens namn eller genre, utan spelen ska ligga, med en sak per rad, i sin egen tabell, samt så ska de andra entiterna ligga i sina egna tabeller innehållande sin egen information.

### Instruktioner

1. Skapa ett ER-diagram som visualisera strukturer för er databas. Entiteter, attribut och relationer ska tydligt vara definierade i diagramet.

2. Skapa databasen utifrån ert ER-diagram innehållandes datan som beskrivs nedan.

3. Skapa queries i form av Views som gör så att user stories uppfylls.

### Följande information ska finnas i databasen:

#### Konsoler:

- Nintendo Switch, 2017-03-03, Nintendo
- PlayStation 1, 1994-12-03, Sony
- Super Nintendo, 1990-11-21, Nintendo
- Xbox 360, 2005-11-22, Microsoft

#### Genre

- Platformer,
- Open-World,
- Arcade,
- Action,
- Shooter,
- RPG,
- Simulation

#### Nintendo Switch har:

- Super Mario Odyssey, Platformer
- Yoshi’s Crafted world, Platformer
- Zelda: Breath of the Wild, Open-World
- Tetris 99, Arcade

#### PlayStation 1 har:

- Crash Bandicoot 1, Platformer
- Crash Bandicoot 3 Warped, Platformer
- Spyro the Dragon, Platformer
- Metal Gear Solid, Action

#### Super Nintendo har:

- Super Mario World, Platformer
- Secret of Mana, RPG
- EarthBound, RPG

#### Xbox 360 har:

- ßViva Pinata, Simulation
- ßHalo 4, Shooter
