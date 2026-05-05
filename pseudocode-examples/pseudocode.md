
## Kasta en tärning tre gånger och räkna ihop det totala värdet

### Version 1

START
    Sätt summa till 0
    Kasta tärning och returnera tärningsresultat (siffran 1-6)
    Sätta summa till tärningsresultat
    Kasta tärning och returnera tärningsresultat
    Sätt summa till summa + tärningsresultat
    Kasta tärning och returnera tärningsresultat
    Sätt summa till summa + tärningsresultat
    Skriv ut summa // Visa på skärmen för användaren
SLUT

## Version 2

START
    Sätt summa till 0
    Iterera 3 gånger:
        Kasta tärning och returnera tärningsresultat
        Sätt summa till summa + tärningsresultat
    Skriv ut summa
SLUT

## Högt eller lågt

Fråga användaren efter ett tal mellan 1 och 100. Programmet ska ha ett hemligt tal sparat. Det ska fortsätta fråga användaren till dess att användaren gissar det hemliga talet. Om man gissade för högt eller för lågt så ska det skrivas ut, så att användaren har en rimlig chans att klara det.

START
    Slumpa ett hemligt tal och spara detta
    Iterera tills användarens tal är lika med hemligt tal:
        Fråga användaren om ett tal (1 - 100) och spara detta
        Om användarens tal är lägre än hemligt tal:
            Skriv ut "Talet är högre"
        Om användarens tal är högre än hemligt tal:
            Skriv ut "Talet är lägre"
        Om användarens tal är lika med hemligt:
            Skriv ut "Du gissade rätt"
SLUT