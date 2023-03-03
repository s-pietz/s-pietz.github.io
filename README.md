# Skylar Pietz's Webpage 

This is a page where I will share some information about myself and the work I am doing in Bioinformatics. So far, I've done some work to analyze data on Penguins and some other datasets including Great Lakes Fish species. 

## Work with Penguins 

I started learning how to use R code by working with the Palmer Penguins data set. We ran an analysis using a small subset of 44 penguins. If you're interested, you can view my analayis [here](https://s-pietz.github.io/BioStatisticsAnalysis/Penguins_Analysis2_1_17.html).

### More on Penguins
This data set on Penguins included 8 features measured on 44 penguins. The features included are physiological features (like bill length, bill depth, flipper length, body mass, etc) as well as other features like the year that the penguin was observed, the island the penguin was observed on, the sex of the penguin, and the species of the penguin. We were able to ask many different questions regarding the penguins. Some questions that we formulated as a class in order to better understand the data we were working with included:
+ What is the average flipper length? What about for each species?
+ Are there more male or female penguins? What about per island or species?
+ What is the average body mass? What about by island? By species? By sex?
+ What is the ratio of bill length to bill depth for a penguin? What is the overall average of this metric? Does it change by species, sex, or island?
+ Does average body mass change by year?

I ejoyed creating these questions in order to guide our analysis and facilitate our learning on how to use R code and manipulate data in this section. Specifically, we learned how to filter rows, subset columns, group data, and compute summary statistics. Remeber to check out my full analysis [here](https://s-pietz.github.io/BioStatisticsAnalysis/Penguins_Analysis2_1_17.html).

## Work with Great Lakes Fish

I then began an alaysis with a data set of various species of fish found in the Great Lakes regions. If you're also interested in this data, you can view my analysis [here](https://s-pietz.github.io/BioStatisticsAnalysis/GreatLakesFish.rmarkdown). 


Alt-H1
======

Alt-H2
------

## Emphasis 

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Stikethrough~~

## Blockquotes

>> ...by using additional greater-than signs right next to each other...
>>> ... or with spaces between arrows. 

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 

## Lists 

Unordered

+ Create a list by starting a line with '+', '-', or '*'
+ Sublists are made by indenting 2 spaces:
  - Marker character change forces new list starts 
    
1. First ordered list item
2. Another item
  * Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
  1. Ordered sub-list
4. And another item.  
   
   Some text that should be aligned with the above item.

* Unordered list can use asterisks
- Or minuses
+ Or pluses

## Code

Inline 'code'

Indented code 

    // Some comments 
    line 1 of code
    line 2 of code
    line 3 of code
 
Block code "fences"

```
Sample text here...
```

Syntax highliting

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

## Tables

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

## Links

[I'm an inline-style link](https://www.google.com)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

## Images

Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

## THE END
