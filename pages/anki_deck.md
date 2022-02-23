---
layout: page
subtitle: retrieve gender and plurals with audio on the go
title: ANKI Deck of Most Spoken German Nouns
bigimg: "https://giselaortt.github.io/images/capas/salinas_nuvem.jpg"
share-img: "https://giselaortt.github.io/images/german_flag.png"
---


## Motivation:

As mentioned in my previous post I have taken too long to initiate on german grammar, as I thought it was not as important. I wasn't aware that the german articles can switch gender according to case(the articles die become der in dative and genitiv!) and now I ended up learning several words as masculine when in reality they are feminim.<br>
It is indeed a commom problem among german learners, as the plurals in german do not obbey any rule, and the genders are so important for the correctedness of the sentences. As the only previous deck I could find with this content carried several mistakes, I decided to implement my own.
<br>

## This deck:

This deck is not intended to learn the meaning of words, instead to learn to retrieve the gender and plural of each german noun(although it contains the english translation). It contains more than 2 thousand german nouns.<br>
The audio is included on my template, all you need is to have [awesomeTTS](https://ankiweb.net/shared/info/814349176) installed and access to internet.<br>
And here is the [anki deck](SOON) to download!
<br>

## Implementation:

I used python to parse the flashcards and beautifulsoup to scrap the information about the plurals, since the book does not contains the plurals.<br>
The list of nouns came from this book: [A Frequency Dictionary of German](https://www.amazon.com.br/Frequency-Dictionary-German-Vocabulary-Learners/dp/0415316332)<br>
But I got them already parsed from this other deck: [A Frequency Dictionary of German](https://ankiweb.net/shared/info/912352287)<br>
Plurals were taken from this website: [Verbformen](https://www.verbformen.pt/declinacao/substantivos/Kenntnis.htm)<br>
Check the code at my [github!](https://github.com/giselaortt/Tools-for-Anki/tree/main/eliminate_repetitions)<br>
The code can be easily adapted to create flashcards in other languages.<br>
