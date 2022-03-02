---
layout: page
subtitle: retrieve gender and plurals with audio on the go
title: ANKI Deck of Most Spoken German Nouns
bigimg: ["/images/capas/por-do-sol.jpg",
          "/images/capas/chile-montanhas.jpg" : "Pumamarca, Chile - 2019",
          "/images/capas/pico-do-papagaio.jpg" : "Pico do Papagayo, Ilha Grande, RJ - 2021",
          "/images/capas/mirante-janela-chapada-veadeiros.jpg" : "Chapada dos veadeiros - 2021",
          "/images/capas/vale-da-lua.jpg" : "Chapada dos veadeiros - 2021",
          "/images/capas/gavea.jpg" : "RJ - 2021",
          "/images/capas/salinas.jpg" : "Salinas grandes - 2019",
          "/images/capas/salinas_nuvem.jpg" : "Salinas grandes - 2019",
          "/images/capas/tirolesa_ponta_grossa.jpg" : "Ponta Grossa, PA - 2021",
          "/images/capas/riodejaneiro.jpg" : "RJ - 2021",
          "/images/capas/salinas-azul.jpg" : "Salinas grandes - 2019",
          "/images/capas/chile-vale-da-lua.jpg" :  "San Pedro de Atacama - 2019",
          "/images/capas/chile-lhamas.jpg" : "San Pedro de Atacama - 2019",
          "/images/capas/bahia-nascer-do-sol.jpg" : "Bahia - 2019" ]
share-img: "/images/german_flag.png"
---


## Motivation:

As mentioned in my previous post I have taken too long to initiate on german grammar, as I thought it was not as important. I wasn't aware that the german articles can switch gender according to case(the articles die become der in dative and genitiv!) and now I ended up learning several words as masculine when in reality they are feminim.<br>
It is indeed a commom problem among german learners, as the plurals in german do not obbey any rule, and the genders are so important for the formation os cases (dative, genitiv, etc.). As the only previous deck I could find with this content carried several mistakes, I decided to implement my own.
<br>

## This deck:

This deck is not intended to learn the meaning of words, instead to learn to retrieve the gender and plural of each german noun(although it contains the english translation). It contains more than 2 thousand german nouns.<br>
The audio is included on my template, all you need is to have [awesomeTTS](https://ankiweb.net/shared/info/814349176) installed and access to internet.<br>
And here is the [anki deck](https://ankiweb.net/shared/info/670301379) to download!
<br>
Since they came from an automatic parsing the deck is expected to contain a few mistakes. I have corrected manually the ones I could find, But I count on german learning comunity to help me check the rest of the deck. Please email me if you find any errors so I can update the deck right away. <br>


## Implementation:

The list of nouns and the translations came from this book: [A Frequency Dictionary of German](https://www.amazon.com.br/Frequency-Dictionary-German-Vocabulary-Learners/dp/0415316332)<br>
But I got them already parsed from this other deck: [A Frequency Dictionary of German](https://ankiweb.net/shared/info/912352287)<br>
I used python to parse the flashcards and beautifulsoup to scrap the information about the plurals, taken from this website: [Verbformen](https://www.verbformen.pt/declinacao/substantivos/Kenntnis.htm)<br>
Check the code at my [github!](https://github.com/giselaortt/Tools-for-Anki/blob/main/eliminate_repetitions/generate_plurals.py)<br>
The code can be easily adapted to create flashcards in other languages.<br>
