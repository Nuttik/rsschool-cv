# Natalia Repkina #

## Contacts: ##

* Email: pn.88@mail.ru
* Telegram: @PonyoFromSea
* Discord: nata#5333
* GitHub: [Nuttik](https://github.com/Nuttik  "ГитХаб")

## About me ##

I am freelancer web disigner. I create websites for Wordpress and Joomla, make designs in figma.
I was tired of working alone and I wanted to join a team as a frontend worker. I realized that my knowledge wasn't enough for this, so I need to learn the latest technologies based on JS. 
That's why I came to this course.

## Skills: ##
* HTMl,CSS
* JavaScript (Basic)
* Figma, Adobe Photoshop, Adobe Illustrator

## Code Example ##

Ката from codewars "Count the number of Duplicates": 

> Write a function that will return the count of distinct case-insensitive alphabetic characters and numeric digits that occur more than once in the input string. The input string can be assumed to contain only alphabets (both uppercase and lowercase) and numeric digits.

### My solution

    function duplicateCount(text) {
      text = text.toLowerCase();
      let arr = text.split("");  
      let double = new Set();
      return arr.reduce(function(count, str, index, array){
        if(index != array.lastIndexOf(str) && !double.has(str)){
          count++;  
          double.add(str);
        }     
        return count; 
      }, 0); 
    }

## Experience ##

* 2011 - 2014 yaers - seo-analyst in wed studio
* 2014 - 2022 yaers - freelanser web disigner. 

## Education ##

Vladimir Pedagogical College
I completed a UI Design course from Tomsk State University last year.

## English ##

A2
