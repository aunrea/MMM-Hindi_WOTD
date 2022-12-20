# Hindi-WordOfTheDay

Author: mjb527 Modified by: aunea

![Example of Result](/img/Word-of-the-Day-Example.png)

## Description

Hindi can be difficulty to learn, so I created this [Magic Mirror](https://github.com/MichMich/MagicMirror) module that scrapes a Hindi Word of the Day from [https://www.hindipod101.com/hindi-phrases/](https://www.hindipod101.com/hindi-phrases/). It formats the Hindi word and sentences, and their English translations, creating a result like the one above, and displays it in the document.

Includes:
1. The word of the day
2. The translation of the word
3. The part of speech (noun, verb, etc.)
4. Examples of how to use it in a sentence, plus the English translation

## Technologies

* JavaScript
* Node.js - including Node Helper, Cheerio, and Request-Promise-Native


## Install

To install this module, clone this repository into the MagicMirror/modules folder.

```
cd MagicMirror/modules
git clone https://github.com/aunrea/MMM-Hindi_WOTD.git
cd MMM-Hindi_WOTD
npm install
npm install request-promise-native
```
To use this module, add the following to the modules array in the config/config.js file:

```
    {
        module: 'MMM-Hindi_WOTD',
        position: 'bottom_right',
        // There are no config options
    }
```
