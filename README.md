### Generate random german words / Generiere zufällige deutsche Wörter (Python)

###### Pip install ready german word generator with a 300.000 word dictionary. 

Try it out in google colabs within your browser --> https://colab.research.google.com/drive/1VbDH18OBfME5m_4oTxMlwDjyW1zbZVxZ?usp=sharing

The according API for the python module with JSON output--> https://zufallsworte.herokuapp.com/

(Give it some time to load and if it fails try visit the URL again)

<br> 


<p align="center">
    <a href="https://github.com/MaximilianFreitag/Zufallswort">
        <img src="https://github.com/MaximilianFreitag/Zufallswort/blob/main/image_gen.jpg">
    </a>
</p>


<!-- GETTING STARTED -->
## Getting Started


1. Pip install with
   ```sh
   pip install zufallsworte
   ```

2. Import the library with
   ```sh
   import zufallsworte as zufall
   ```

<br> 
________________________________________________________________
<br>  
 
   
<!-- How to use -->
## How to use
   
<br>
Return one random german word

    zufall.zufallswoerter(1)
    
    --> Katze

<br> 

Return 5 random german words 
 
    zufall.zufallswoerter(5)
    
    --> ['rot', 'Baum', 'Eichhörnchen', 'Brötchen', 'Auto']

<br> 

Return 3 random german words that start with certain letters 

    zufall.anfangsbuchstaben('herum', 3)
    
    ['herumtragen', 'herumnörgeln', 'Herumtreiber']

<br> 

Return 3 random german words that end with certain letters 

    zufall.endbuchstaben('legen', 2)
    
    --> ['anlegen', 'hinzulegen']


<br> 

Return 2 random german words that contain the letters "ff"


    zufall.enthaelt_buchstaben('ff', 2)
    
    --> ['Schiff', 'Affinität']

<br> 

Return 3 random german words that are exactly 7 characters long


    zufall.anzahl_buchstaben(7, 3)
    
    --> ['Biomüll', 'fließen', 'Rotwein']


<br />
<br />
<br />


__________________________________________________

<br />

<!-- Supported versions -->
## Supported versions of Python 🐍

Python 3+


<br>




__________________________________________________

<br />

<!-- Current bugs -->
## Current bugs 🐞

None

<br>

__________________________________________________


<br />
<br />

## Stargazers over time

[![Stargazers over time](https://starchart.cc/MaximilianFreitag/Zufallswort.svg)](https://starchart.cc/MaximilianFreitag/Zufallswort)





<br />
<br />
#Generator #deutsch #zufällig #Wörter #duden #wortliste #txt #Pipinstall #python #python3  
<br />
<br />



## License
This project falls under the MIT license.




