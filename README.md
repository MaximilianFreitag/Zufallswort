# Generate random german words / Generiere zufällige deutsche Wörter

<br> 

<!-- GETTING STARTED -->
## Getting Started


1. Pip install with
   ```sh
   pip install zufallsworte
   ```

2. Install the library with
   ```sh
   import zufallsworte as zufall
   ```
   
________________________________________________________________________________________________________________
<br>  
 
   
<!-- How to use -->
## How to use
   
<br>
Return one random word

    zufall.zufallswort(1)


Return 5 random words 
 
    zufall.zufallswort(5)

Return 3 random words that start with certain letters 

    zufall.anfangsbuchstaben('herum', 3)

Returns 3 random words that end with certain letters 

    zufall.anfangsbuchstaben('legen', 3)


Returns 2 random words that contain the letters "ff"


    zufall.enthält_buchstaben('ff', 2)

Return 3 random words that are exactly 7 characters long


    zufall.anzahl_buchstaben(7, 3)







