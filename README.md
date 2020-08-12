# Open Psychometrics Fictional Characters Ratings
### Final Project for Mary Ting 

For my Final Project, I chose a fun dataset based on crowdsourced fictional character analysis that I found through Data is PLural. I had first heard of this through a quiz on openpsychometrics.org a few months back. You answer 30 questions about yourself and the results show you what fictional characters you are most like. The quiz can be found here: https://openpsychometrics.org/tests/characters/

They give you your results, here are mine.

![](https://media.journalism.berkeley.edu/upload/2020/08/1597209416df6bc1c.png) 

Then you're asked  to analyze characters. Here's some examples. 

![](https://media.journalism.berkeley.edu/upload/2020/08/15972091669a653d7.png)
![](https://media.journalism.berkeley.edu/upload/2020/08/15972095043b8a9c7.jpg)
![](https://media.journalism.berkeley.edu/upload/2020/08/15972095380bb7e71.jpg)

There are over 200 character traits measured for each fictional character and while some are obvious (straight vs. queer, masculine vs. femine) some are aloof and downright entertaining (proletraiat vs. bourgeoisie, philosophical vs, real, spicy vs. mild, etc) 

All the data for every Fictional Works and characters was compiled into a zip file that contained a CSV of the raw data and a codebook.

[Here's a link to my data.](https://drive.google.com/file/d/1TjTki1PXDLsQdKwqjRiLyo4X3-ioB6Xc/view?usp=sharing)

The most difficult part was turning the codebook into a CSV and making it separate sheets so I could use formulas to make the data legible.

The formulas I used were 

=VLOOKUP(A4,'character index'!A1:C801,3, false)
```
=VLOOKUP(I$1,'trait index'!A1:E235,2, false)
```

I had a BLAST looking through this data. Here are some highlights. 

#### Most Masculine 

| Fictional Work | Character   | Average Rating  |
| ------------- |:-------------:| -----:|
| Parks and Rec   | Ron Swanson| 3 |
| Star Trek TNG | Worf     |   4.6 |
| Friday Night Lights | Tim Riggins     |    4.9 |
| Prison Break | Lincoln Burrow    |    5 |

#### Most Feminine 

| Fictional Work | Character   | Average Rating  |
| ------------- |:-------------:| -----:|
| Schitt's Creek   | Alexis Rose | 92.2|
| That 70s Show  | Jackie Burkham    |   90.2|
| Friday Night Lights| Lyla Garrity     |   95.6 |
| HUnger Games | Effie Trinket  |    95.4 |

#### Most Extroverted 

| Fictional Work | Character   | Average Rating  |
| ------------- |:-------------:| -----:|
| Sex in the City    | Samantha Jones | 5.5|
| Crazy Rich Asians   | Goh Pek Lin    |   5.7|
| Parks and Rec | Tom Haverford     |    5.7 |
| Brooklyn 99 | Jake Peralta   |   6 |

#### Most Introverted

| Fictional Work | Character   | Average Rating  |
| ------------- |:-------------:| -----:|
| Scandal  | Huck | 92.2 |
| Twilight    | Bella Swan   |   89.3|
| Harry Potter | Severus Snape     |    89.3 |
| Pride and Prejudice | Mr. Darcy     |   89.1|
| Game of Thrones | Brandon Stark   |  89 |

#### Most Hipster (as opposed to Basic)

| Fictional Work | Character   | Average Rating  |
| ------------- |:-------------:| -----:|
| Friends   | Phoebe Buffay | 12.4 |
| Harry Potter    | Nymphadora Tonks      |  12.8|
| Harry Potter | Luna Lovegood      |   13.6|
| Girls |  Jessa Johansson    |    13.7 |
| Mean Girls |Janis Ian     |    14.1 |

#### Alpha

| Fictional Work | Character   | Average Rating  |
| ------------- |:-------------:| -----:|
| Scandal | Olivia Pope | 4.9 |
| Alien   |the Alien   | 5.2  |
|Downton Abbey | Violet Crawley, Dowager Countes of Grantham     |  5.7|
| Mean Girls | Regina George    |    6 |
| The Lion King  | Mufasa      |    7 |

#### Beta 

| Fictional Work | Character   | Average Rating  |
| ------------- |:-------------:| -----:|
| Arrested Development     | Buster Bluth | $94.3|
|The Simpsons   | Milhouse Van Houten      |   94.1 |
| Brooklyn 99| Charles Boyle     |    93.5 |
| Star Wars | C-3PO   |    87.6 |

#### Bossy (as opposed to Meek) 

| Fictional Work | Character   | Average Rating  |
| ------------- |:-------------:| -----:|
|Game of Thrones    | Cersei Lannister | 77.7|
| Mean Girls  | Regina George   |   66.3 |
| Arrested Development  | Lucille Bluth      |    66.7 |
| Harry Potter | Dolores Umbridge    |    87.4 |

#### Master (as opposed to Apprentice) 

| Fictional Work | Character   | Average Rating  |
| ------------- |:-------------:| -----:|
| Lord of the Rings    | Gandalf | 95.6 |
| Prison Break  | Michael Scofield       |   95.5|
| House, M.D. | Dr. Gregory House    |   95.5|
| Parks and Rec| Ron Swanson   |   95.2|
| Harry Potter | Albus Dumbledore   |  94.8|
| NCIS | Leroy Jethro Gibbs  |   94.8|


<iframe title="The Office -Competence and Work Ethic " aria-label="chart" id="datawrapper-chart-pv8gS" src="https://datawrapper.dwcdn.net/pv8gS/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="442"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>
