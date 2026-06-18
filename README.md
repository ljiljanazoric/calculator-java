# Izvestaj o statickoj analizi koda

**Ukupni LOC projekta:** 50 linija koda

### Zapazanja i Code Smells:
- Calculator.java - Deljenje sa nulom - Metoda za deljenje nema uslov "if (b == 0)" što dovodi do pada aplikacije u slučaju deljenja sa nulom.
- Start.java - Magic Numbers - Prosledjuju se fiksne numericke vrednosti direktno u metode bez koriscenja varijabli.
- Calculator.java - Imenovanje varijabli - Koriscenje generickih imena (a, b) umesto opisnih naziva parametara.
