---
title: "Lecture 5"
subtitle: "Game Theory"
author: "Dr Cillian McHugh"
institute: "PS4168: Economic Psychology"
bibliography: "resources/bib/My Library.bib"
csl: apa.csl
format: 
  revealjs:
    slide-number: false
    logo: "resources/images/ul-psychology-logos.png"
    footer: "PS4168: Cillian McHugh - 11/10/23"
    theme: "resources/css/mytheme.scss"
    incremental: false
    chalkboard: 
      buttons: true
editor: source
---




<style type="text/css">
    table.table-style-one {
        font-size:36px;
        color:#333333;
        border-width: 1px;
        border-color: #D3D3D3;
        border-collapse: collapse;
    }
    table.table-style-one th {
        border-width: 1px;
        padding: 16px;
        border-style: solid;
        border-color: #3A3A3A;
        background-color: #B3B3B3;
    }
    table.table-style-one td {
        border-width: 1px;
        padding: 16px;
        border-style: solid;
        border-color: #D3D3D3;
        background-color: #ececec;
    }
</style>






## Game Theory


<iframe width="900" height="600" src="https://www.youtube.com/embed/AJ5aIvjNgao?si=RWOztM-oMpazRJZ_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


## Key Concepts in Todays lecture / Overview



- Strict Dominance

- Nash Equilibrium

- Mixed Strategy Nash Equilibrium

- Predicting others' behaviour

- In-class Activities

## Recap on last week!{.smaller}

- Definition of Rationality?
  + Instrumental rationality
      + "our mental states or processes are rational when they help us to achieve our goals" <font size=4.5>[@over_rationality_2004, p. 3]</font size>

- Two approaches to the study of decision making
  + <font color="B93B8F">Normative</font> Theories *versus* <font color="2FAACE">Behavioural</font> Theories
- Theories of decision making
  + <font color="B93B8F">Expected Value / Expected Utility</font>
  + <font color="2FAACE">Prospect Theory</font>
  + <font color="2FAACE">Social Functionalist Theory</font>

# Introduction to Game Theory

## Introduction to Game Theory



- Branch of Applied Mathematics
  - Provides a framework for modelling and predicting behaviour in Social situations of 
      - cooperation
      - coordination
      - conflict <br>[@dowling_modern_2007; @vonneuman_theory_1944; @vonneuman_theories_1947]

# The Prisoner Dilemma

## The Prisoner Dilemma{.smaller}



- Two suspects (e.g., <font color="#6666ff">Bob</font> and <font color="#ff4c4c">Susan</font>) are arrested on suspicion of a serious crime

- However:
  - Only sufficient evidence to convict them of a minor crime
  
- Prisoners are kept in isolation and offered a deal:
  - If neither confess they each get 1 year
  - If one confesses and the other doesn't the one that confessed will be let free and the other is sentenced for 20 years
  - If they both confess they each get 5 years

[adapted from @dowling_modern_2007; originally devised by Merrill Flood and Melvin Dresher in 1950 see @dowling_modern_2007, p. 107]

## The Prisoner Dilemma



[https://app.sli.do/event/aDybaWhRyTBynrEGdd5vPX](https://app.sli.do/event/aDybaWhRyTBynrEGdd5vPX)

## The Prisoner Dilemma

<iframe width="900" height="600" src="https://wall.sli.do/event/aDybaWhRyTBynrEGdd5vPX?section=7aa51d4d-d1d3-4db7-8a71-f02fcd57b123" frameborder="0" allow="autoplay; encrypted-media"></iframe>




## The Prisoner Dilemma



<br>
<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>keep quiet</font></td>
<td align="center"><font size = 5px>confess</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>keep quiet</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">-1</font></td>
<td align="center"><font color="#6666ff">-20</font> , <font color="#ff4c4c">0</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>confess</font></td>
<td align="center"><font color="#6666ff">0</font> , <font color="#ff4c4c">-20</font></td>
<td align="center"><font color="#6666ff">-5</font> , <font color="#ff4c4c">-5</font></td>
</tr>
</table>
</center>
<br>
[adapted from @dowling_modern_2007, p. 108]

## Strict Dominance

:::{.incremental}

- The strategy x is a **dominant** strategy if it is a *strict best response* to any feasible strategy that the others might play
- We say that a strategy x strictly dominates strategy y for a player if
  - strategy x provides a greater payoff for that player than strategy y
  - regardless of what the other player(s) do.


- **What is the dominant strategy in the Prisoner Dilemma?**

:::

## The Prisoner Dilemma and Strict Dominance



Work through possibilities

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>keep quiet</font></td>
<td align="center"><font size = 5px>confess</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>keep quiet</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">-1</font></td>
<td align="center"><font color="#6666ff">-20</font> , <font color="#ff4c4c">0</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>confess</font></td>
<td align="center"><font color="#6666ff">0</font> , <font color="#ff4c4c">-20</font></td>
<td align="center"><font color="#6666ff">-5</font> , <font color="#ff4c4c">-5</font></td>
</tr>
</table>
</center>
<br>
[adapted from @dowling_modern_2007, p. 108]

# Player 1's Options

## Player 1's Options



If Player 2 Keeps Quiet...

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>keep quiet</font></td>
<td align="center"><font size = 5px>confess</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>keep quiet</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">-1</font></td>
<td align="center"><font color="#6666ff">-20</font> , <font color="#ff4c4c">0</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>confess</font></td>
<td align="center"><font color="#6666ff">0</font> , <font color="#ff4c4c">-20</font></td>
<td align="center"><font color="#6666ff">-5</font> , <font color="#ff4c4c">-5</font></td>
</tr>
</table>
</center>
<br>
[adapted from @dowling_modern_2007, p. 108]

## (1) Player 1's Options



Options available to Player 1 if Player 2 Keeps Quiet

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>**keep quiet**</font></td>
<td align="center"><font size = 5px color = "#D3D3D3">confess</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>keep quiet</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#D3D3D3">-1</font></td>
<td align="center"><font color="#D3D3D3">-20</font> , <font color="#D3D3D3">0</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>confess</font></td>
<td align="center"><font color="#6666ff">0</font> , <font color="#D3D3D3">-20</font></td>
<td align="center"><font color="#D3D3D3">-5</font> , <font color="#D3D3D3">-5</font></td>
</tr>
</table>
</center>
<br>
[adapted from @dowling_modern_2007, p. 108]

## (2) Player 1's Options



Player 1 is better off to confess

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>**keep quiet**</font></td>
<td align="center"><font size = 5px color = "#D3D3D3">confess</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px color = "#D3D3D3" >keep quiet</font></td>
<td align="center"><font color="#D3D3D3">-1</font> , <font color="#D3D3D3">-1</font></td>
<td align="center"><font color="#D3D3D3">-20</font> , <font color="#D3D3D3">0</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>confess</font></td>
<td align="center"><font color="#6666ff">0*</font> , <font color="#D3D3D3">-20</font></td>
<td align="center"><font color="#D3D3D3">-5</font> , <font color="#D3D3D3">-5</font></td>
</tr>
</table>
</center>
<br>
[adapted from @dowling_modern_2007, p. 108]


## (3) Player 1's Options



Options available to Player 1 if Player 2 Confesses

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px color = "#D3D3D3">keep quiet</font></td>
<td align="center"><font size = 5px>**confess**</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>keep quiet</font></td>
<td align="center"><font color="#D3D3D3">-1</font> , <font color="#D3D3D3">-1</font></td>
<td align="center"><font color="#6666ff">-20</font> , <font color="#D3D3D3">0</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>confess</font></td>
<td align="center"><font color="#D3D3D3">0*</font> , <font color="#D3D3D3">-20</font></td>
<td align="center"><font color="#6666ff">-5</font> , <font color="#D3D3D3">-5</font></td>
</tr>
</table>
</center>
<br>
[adapted from @dowling_modern_2007, p. 108]

## (4) Player 1's Options



Player 1 is better off to confess

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px color = "#D3D3D3">keep quiet</font></td>
<td align="center"><font size = 5px>**confess**</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px color = "#D3D3D3">keep quiet</font></td>
<td align="center"><font color="#D3D3D3">-1</font> , <font color="#D3D3D3">-1</font></td>
<td align="center"><font color="#D3D3D3">-20</font> , <font color="#D3D3D3">0</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>confess</font></td>
<td align="center"><font color="#D3D3D3">0*</font> , <font color="#D3D3D3">-20</font></td>
<td align="center"><font color="#6666ff">-5*</font> , <font color="#D3D3D3">-5</font></td>
</tr>
</table>
</center>
<br>
[adapted from @dowling_modern_2007, p. 108]

## (5) Player 1's Options



Confess is **Strictly Dominant** for Player 1

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>keep quiet</font></td>
<td align="center"><font size = 5px>confess</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px color = "#D3D3D3">keep quiet</font></td>
<td align="center"><font color="#D3D3D3">-1</font> , <font color="#D3D3D3">-1</font></td>
<td align="center"><font color="#D3D3D3">-20</font> , <font color="#D3D3D3">0</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>**confess**</font></td>
<td align="center"><font color="#6666ff">0*</font> , <font color="#D3D3D3">-20</font></td>
<td align="center"><font color="#6666ff">-5*</font> , <font color="#D3D3D3">-5</font></td>
</tr>
</table>
</center>
<br>
[adapted from @dowling_modern_2007, p. 108]




# Player 2's Options

## Player 2's Options



If Player 1 Keeps Quiet

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>keep quiet</font></td>
<td align="center"><font size = 5px>confess</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>keep quiet</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">-1</font></td>
<td align="center"><font color="#6666ff">-20</font> , <font color="#ff4c4c">0</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>confess</font></td>
<td align="center"><font color="#6666ff">0</font> , <font color="#ff4c4c">-20</font></td>
<td align="center"><font color="#6666ff">-5</font> , <font color="#ff4c4c">-5</font></td>
</tr>
</table>
</center>
<br>
[adapted from @dowling_modern_2007, p. 108]

## (1) Player 2's Options



Options available to Player 2 if Player 1 Keeps Quiet

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>keep quiet</font></td>
<td align="center"><font size = 5px>confess</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>**keep quiet**</font></td>
<td align="center"><font color="#D3D3D3">-1</font> , <font color="#ff4c4c">-1</font></td>
<td align="center"><font color="#D3D3D3">-20</font> , <font color="#ff4c4c">0</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px color = "#D3D3D3">confess</font></td>
<td align="center"><font color="#D3D3D3">0</font> , <font color="#D3D3D3">-20</font></td>
<td align="center"><font color="#D3D3D3">-5</font> , <font color="#D3D3D3">-5</font></td>
</tr>
</table>
</center>
<br>
[adapted from @dowling_modern_2007, p. 108]

## (2) Player 2's Options



Player 2 is better off to confess

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px color="#D3D3D3">keep quiet</font></td>
<td align="center"><font size = 5px>confess</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>**keep quiet**</font></td>
<td align="center"><font color="#D3D3D3">-1</font> , <font color="#D3D3D3">-1</font></td>
<td align="center"><font color="#D3D3D3">-20</font> , <font color="#ff4c4c">0*</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px color = "#D3D3D3">confess</font></td>
<td align="center"><font color="#D3D3D3">0</font> , <font color="#D3D3D3">-20</font></td>
<td align="center"><font color="#D3D3D3">-5</font> , <font color="#D3D3D3">-5</font></td>
</tr>
</table>
</center>
<br>
[adapted from @dowling_modern_2007, p. 108]


## (3) Player 2's Options



Options available to Player 2 if Player 1 Confesses

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>keep quiet</font></td>
<td align="center"><font size = 5px>confess</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px color = "#D3D3D3">keep quiet</font></td>
<td align="center"><font color="#D3D3D3">-1</font> , <font color="#D3D3D3">-1</font></td>
<td align="center"><font color="#D3D3D3">-20</font> , <font color="#D3D3D3">0*</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>**confess**</font></td>
<td align="center"><font color="#D3D3D3">0</font> , <font color="#ff4c4c">-20</font></td>
<td align="center"><font color="#D3D3D3">-5</font> , <font color="#ff4c4c">-5</font></td>
</tr>
</table>
</center>
<br>
[adapted from @dowling_modern_2007, p. 108]


## (4) Player 2's Options



Player 2 is better off to confess

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px color="#D3D3D3">keep quiet</font></td>
<td align="center"><font size = 5px>confess</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px color = "#D3D3D3">keep quiet</font></td>
<td align="center"><font color="#D3D3D3">-1</font> , <font color="#D3D3D3">-1</font></td>
<td align="center"><font color="#D3D3D3">-20</font> , <font color="#D3D3D3">0*</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>**confess**</font></td>
<td align="center"><font color="#D3D3D3">0</font> , <font color="#D3D3D3">-20</font></td>
<td align="center"><font color="#D3D3D3">-5</font> , <font color="#ff4c4c">-5*</font></td>
</tr>
</table>
</center>
<br>
[adapted from @dowling_modern_2007, p. 108]

## (5) Player 2's Options



Confess is **Strictly Dominant** for Player 2

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px color = "#D3D3D3">keep quiet</font></td>
<td align="center"><font size = 5px>**confess**</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>keep quiet</font></td>
<td align="center"><font color="#D3D3D3">-1</font> , <font color="#D3D3D3">-1</font></td>
<td align="center"><font color="#D3D3D3">-20</font> , <font color="#ff4c4c">0*</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>confess</font></td>
<td align="center"><font color="#D3D3D3">0</font> , <font color="#D3D3D3">-20</font></td>
<td align="center"><font color="#D3D3D3">-5</font> , <font color="#ff4c4c">-5*</font></td>
</tr>
</table>
</center>
<br>
[adapted from @dowling_modern_2007, p. 108]

## Combining the Options



Recall that Confess is **Strictly Dominant** for Player 1

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>keep quiet</font></td>
<td align="center"><font size = 5px>confess</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px color = "#D3D3D3">keep quiet</font></td>
<td align="center"><font color="#D3D3D3">-1</font> , <font color="#D3D3D3">-1</font></td>
<td align="center"><font color="#D3D3D3">-20</font> , <font color="#D3D3D3">0</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>**confess**</font></td>
<td align="center"><font color="#6666ff">0*</font> , <font color="#D3D3D3">-20</font></td>
<td align="center"><font color="#6666ff">-5*</font> , <font color="#D3D3D3">-5</font></td>
</tr>
</table>
</center>
<br>
[adapted from @dowling_modern_2007, p. 108]


## Combining the Options



And that Confess is also  **Strictly Dominant** for Player 2

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px color = "#D3D3D3">keep quiet</font></td>
<td align="center"><font size = 5px>**confess**</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>keep quiet</font></td>
<td align="center"><font color="#D3D3D3">-1</font> , <font color="#D3D3D3">-1</font></td>
<td align="center"><font color="#D3D3D3">-20</font> , <font color="#ff4c4c">0*</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>confess</font></td>
<td align="center"><font color="#6666ff">0*</font> , <font color="#D3D3D3">-20</font></td>
<td align="center"><font color="#6666ff">-5* </font> , <font color="#ff4c4c"> -5* </font></td>
</tr>
</table>
</center>
<br>
[adapted from @dowling_modern_2007, p. 108]


## Combining the Options



This leaves `<confess><confess>` as the ***Rational*** outcome

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px color = "#D3D3D3">keep quiet</font></td>
<td align="center"><font size = 5px>**confess**</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px color="#D3D3D3">keep quiet</font></td>
<td align="center"><font color="#D3D3D3">-1</font> , <font color="#D3D3D3">-1</font></td>
<td align="center"><font color="#D3D3D3">-20</font> , <font color="#D3D3D3">0*</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>**confess**</font></td>
<td align="center"><font color="#D3D3D3">0*</font> , <font color="#D3D3D3">-20</font></td>
<td align="center"><font color="#6666ff">-5* </font> , <font color="#ff4c4c"> -5* </font></td>
</tr>
</table>
</center>
<br>
[adapted from @dowling_modern_2007, p. 108]



# Alternatives to the Prisoner Dilemma

## Some Alternatives to the Prisoner Dilemma



- Import Tax

- Advertising

- International Relations<br>[taken from @spaniel_game_2013]

- Any other examples?

## Import Tax{.smaller}



- Should countries introduce tax on imports/trading tariffs?
- Placing tariffs (a tax) on imported goods can
  - protect domestic industries 
  - though this leads to higher prices overall
- The best outcome for a country is to tax imports while not having the other country tax its exports.
- Free trade is the next best outcome
- Mutual tariffs is the next best outcome
  - ultimately, this leads to higher prices than the free trade outcome
- The worst possible outcome is to levy no taxes while the other country enforces a tariff



## Import Tax




<br>
<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Country 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>No Tax</font></td>
<td align="center"><font size = 5px>Tax</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Country 1</font></td>
<td align="center"><font size = 5px>No Tax</font></td>
<td align="center"><font color="#6666ff">3</font> , <font color="#ff4c4c">3</font></td>
<td align="center"><font color="#6666ff">1</font> , <font color="#ff4c4c">4</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Tax</font></td>
<td align="center"><font color="#6666ff">4</font> , <font color="#ff4c4c">1</font></td>
<td align="center"><font color="#6666ff">2</font> , <font color="#ff4c4c">2</font></td>
</tr>
</table>
</center>


## Advertising{.smaller}



- Consider two rival firms considering whether to advertise their products
- Would the firms ever want the government to pass a law forbidding advertisement?
- If advertising campaigns only persuade a consumer to buy a certain **brand** of product *rather than the product in general*
  - If one side places ads and the other does not, the firm with the advertising campaign cuts into the other’s share of the market.
  - If they both advertise, the ads cancel each other out, but they still have to pay for the campaigns.

## Advertising



<br>
<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Company 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>No Ads</font></td>
<td align="center"><font size = 5px>Ads</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Company 1</font></td>
<td align="center"><font size = 5px>No Ads</font></td>
<td align="center"><font color="#6666ff">4</font> , <font color="#ff4c4c">4</font></td>
<td align="center"><font color="#6666ff">2</font> , <font color="#ff4c4c">5</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Ads</font></td>
<td align="center"><font color="#6666ff">5</font> , <font color="#ff4c4c">2</font></td>
<td align="center"><font color="#6666ff">3</font> , <font color="#ff4c4c">3</font></td>
</tr>
</table>
</center>



## Going to War

:::{.incremental}

- Should two states go to war?
- Peace is preferable to war
- BUT
  - Striking first leads to a large advantage
  - Being struck first is very costly
      - Striking at the same time as opponent is preferable to being attacked

:::

## Going to war



<br>
<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Country 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Defend</font></td>
<td align="center"><font size = 5px>Attack</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Country 1</font></td>
<td align="center"><font size = 5px>Defend</font></td>
<td align="center"><font color="#6666ff">3</font> , <font color="#ff4c4c">3</font></td>
<td align="center"><font color="#6666ff">-3</font> , <font color="#ff4c4c">4</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Attack</font></td>
<td align="center"><font color="#6666ff">4</font> , <font color="#ff4c4c">-3</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">-1</font></td>
</tr>
</table>
</center>

# Asymmetric Games

## Asymmetric Games



<br>
<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Left</font></td>
<td align="center"><font size = 5px>Right</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Up</font></td>
<td align="center"><font color="#6666ff">9</font> , <font color="#ff4c4c">-2</font></td>
<td align="center"><font color="#6666ff">3</font> , <font color="#ff4c4c">0</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Down</font></td>
<td align="center"><font color="#6666ff">8</font> , <font color="#ff4c4c">5</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">6</font></td>
</tr>
</table>
</center>



## Another Asymmetric Game

:::{.incremental}

- Two Clubs <font color="#6666ff">ONE</font> and <font color="#ff4c4c">TWO</font> in a town
- Will run either a Salsa night or a Disco night
- <font color="#6666ff">ONE</font> is centrally located but <font color="#ff4c4c">TWO</font> is outside the town
  - If <font color="#ff4c4c">TWO</font> runs the same night as <font color="#6666ff">ONE</font> nobody will show

- Three types of customers
  - 60 hardcore Salsa fans - will only go to Salsa
  - 20 hardcore Disco fans - will only go to Disco 
  - 20 people prefer going to a disco theme but will attend a salsa night if that is the only option

:::

## Another Asymmetric Game

<br>

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">TWO</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Salsa</font></td>
<td align="center"><font size = 5px>Disco</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">ONE</font></td>
<td align="center"><font size = 5px>Salsa</font></td>
<td align="center"><font color="#6666ff">80</font> , <font color="#ff4c4c">0</font></td>
<td align="center"><font color="#6666ff">60</font> , <font color="#ff4c4c">40</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Disco</font></td>
<td align="center"><font color="#6666ff">40</font> , <font color="#ff4c4c">60</font></td>
<td align="center"><font color="#6666ff">40</font> , <font color="#ff4c4c">0</font></td>
</tr>
</table>
</center>

## Another Asymmetric Game



Iterated Elimination of Strictly Dominated Strategies 

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">TWO</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Salsa</font></td>
<td align="center"><font size = 5px>Disco</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">ONE</font></td>
<td align="center"><font size = 5px>Salsa</font></td>
<td align="center"><font color="#6666ff">80</font> , <font color="#ff4c4c">0</font></td>
<td align="center"><font color="#6666ff">60</font> , <font color="#ff4c4c">40</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Disco</font></td>
<td align="center"><font color="#6666ff">40</font> , <font color="#ff4c4c">60</font></td>
<td align="center"><font color="#6666ff">40</font> , <font color="#ff4c4c">0</font></td>
</tr>
</table>
</center>

## Iterated Elimination of Strictly Dominated Strategies 




<br>
<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td align="center"></td>
<td align="center"><font size = 5px>Left</font></td>
<td align="center"><font size = 5px>Center</font></td>
<td align="center"><font size = 5px>Right</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Up</font></td>
<td align="center"><font color="#6666ff">13</font> , <font color="#ff4c4c">3</font></td>
<td align="center"><font color="#6666ff">1</font> , <font color="#ff4c4c">4</font></td>
<td align="center"><font color="#6666ff">7</font> , <font color="#ff4c4c">3</font></td>
</tr>
<tr class="odd">
<td align = "center"><font size = 5px>Middle</font></td>
<td align="center"><font color="#6666ff">4</font> , <font color="#ff4c4c">1</font></td>
<td align="center"><font color="#6666ff">3</font> , <font color="#ff4c4c">3</font></td>
<td align="center"><font color="#6666ff">6</font> , <font color="#ff4c4c">2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Down</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">9</font></td>
<td align="center"><font color="#6666ff">2</font> , <font color="#ff4c4c">8</font></td>
<td align="center"><font color="#6666ff">8</font> , <font color="#ff4c4c">-1</font></td>
</tr>
</table>
</center>

# Different types of Games

## Stag Hunt{.smaller}

:::{.incremental}

- Two hunters enter a range filled with hares and a single stag
  - Hares are easy to capture
      - but not worth much meat (1)
  - Catching the stag requires working together
      - worth much more meat (6 - to share between 2)
  
- If they both hunt hares, they each capture half of the hares in the range
- If one hunts the stag and the other hunts hares
  - the stag hunter goes home empty-handed
  - the hare hunter captures all of the hares
- If both hunt the stag, they share the stag (value of the stag is greater than the value of all of the hares) 

:::

## Stag Hunt



<br>

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Stag</font></td>
<td align="center"><font size = 5px>Hare</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Stag</font></td>
<td align="center"><font color="#6666ff">3</font> , <font color="#ff4c4c">3</font></td>
<td align="center"><font color="#6666ff">0</font> , <font color="#ff4c4c">2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Hare</font></td>
<td align="center"><font color="#6666ff">2</font> , <font color="#ff4c4c">0</font></td>
<td align="center"><font color="#6666ff">1</font> , <font color="#ff4c4c">1</font></td>
</tr>
</table>
</center>

## Strict Dominace in the Stag Hunt?



<br>

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Stag</font></td>
<td align="center"><font size = 5px>Hare</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Stag</font></td>
<td align="center"><font color="#6666ff">3</font> , <font color="#ff4c4c">3</font></td>
<td align="center"><font color="#6666ff">0</font> , <font color="#ff4c4c">2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Hare</font></td>
<td align="center"><font color="#6666ff">2</font> , <font color="#ff4c4c">0</font></td>
<td align="center"><font color="#6666ff">1</font> , <font color="#ff4c4c">1</font></td>
</tr>
</table>
</center>


## Strict Dominace in the Stag Hunt?



If Player 2 hunts Stag

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>**Stag**</font></td>
<td align="center"><font size = 5px color = "#D3D3D3">Hare</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Stag</font></td>
<td align="center"><font color="#6666ff">3</font> , <font color="#D3D3D3">3</font></td>
<td align="center"><font color="#D3D3D3">0</font> , <font color="#D3D3D3">2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Hare</font></td>
<td align="center"><font color="#6666ff">2</font> , <font color="#D3D3D3">0</font></td>
<td align="center"><font color="#D3D3D3">1</font> , <font color="#D3D3D3">1</font></td>
</tr>
</table>
</center>

## Strict Dominace in the Stag Hunt?



Player 1 should also hunt the Stag

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>**Stag**</font></td>
<td align="center"><font size = 5px color = "#D3D3D3">Hare</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Stag</font></td>
<td align="center"><font color="#6666ff">3*</font> , <font color="#D3D3D3">3</font></td>
<td align="center"><font color="#D3D3D3">0</font> , <font color="#D3D3D3">2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px color="#D3D3D3">Hare</font></td>
<td align="center"><font color="#D3D3D3">2</font> , <font color="#D3D3D3">0</font></td>
<td align="center"><font color="#D3D3D3">1</font> , <font color="#D3D3D3">1</font></td>
</tr>
</table>
</center>

## Strict Dominace in the Stag Hunt?



If Player 2 hunts Hare

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px color = "#D3D3D3">Stag</font></td>
<td align="center"><font size = 5px>**Hare**</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Stag</font></td>
<td align="center"><font color="#D3D3D3">3*</font> , <font color="#D3D3D3">3</font></td>
<td align="center"><font color="#6666ff">0</font> , <font color="#D3D3D3">2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Hare</font></td>
<td align="center"><font color="#D3D3D3">2</font> , <font color="#D3D3D3">0</font></td>
<td align="center"><font color="#6666ff">1</font> , <font color="#D3D3D3">1</font></td>
</tr>
</table>
</center>

## Strict Dominace in the Stag Hunt?



Player 1 should also hunt the Hare

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px color = "#D3D3D3">Stag</font></td>
<td align="center"><font size = 5px>**Hare**</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px color = "#D3D3D3">Stag</font></td>
<td align="center"><font color="#D3D3D3">3*</font> , <font color="#D3D3D3">3</font></td>
<td align="center"><font color="#D3D3D3">0</font> , <font color="#D3D3D3">2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Hare</font></td>
<td align="center"><font color="#D3D3D3">2</font> , <font color="#D3D3D3">0</font></td>
<td align="center"><font color="#6666ff">1*</font> , <font color="#D3D3D3">1</font></td>
</tr>
</table>
</center>

## No Strict Dominace in the Stag Hunt?



Player 1's best strategy depends on Player 2's actions

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Stag</font></td>
<td align="center"><font size = 5px>Hare</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Stag</font></td>
<td align="center"><font color="#6666ff">3*</font> , <font color="#D3D3D3">3</font></td>
<td align="center"><font color="#D3D3D3">0</font> , <font color="#D3D3D3">2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Hare</font></td>
<td align="center"><font color="#D3D3D3">2</font> , <font color="#D3D3D3">0</font></td>
<td align="center"><font color="#6666ff">1*</font> , <font color="#D3D3D3">1</font></td>
</tr>
</table>
</center>

## No Strict Dominace in the Stag Hunt?



Similarly, Player 2's best strategy depends on Player 1's actions

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Stag</font></td>
<td align="center"><font size = 5px>Hare</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Stag</font></td>
<td align="center"><font color="#D3D3D3">3* </font> , <font color="#ff4c4c">3 *</font></td>
<td align="center"><font color="#D3D3D3">0</font> , <font color="#D3D3D3">2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Hare</font></td>
<td align="center"><font color="#D3D3D3">2</font> , <font color="#D3D3D3">0</font></td>
<td align="center"><font color="#D3D3D3">1* </font> , <font color="#ff4c4c">1 *</font></td>
</tr>
</table>
</center>

## No Strict Dominace in the Stag Hunt?{.smaller}

:::{.incremental}

- **Nash equilibrium**
  - a set of strategies, one for each player
  - no player has incentive to change his or her strategy (given what the other players are doing)
  
- **Nash equilibrium** is the best strategy given the strategy chosen by the other participants<br><font size=4.5>[@dowling_modern_2007]</font size>

- Individuals have no incentive to deviate (not group deviations)
  - no regrets at the end of the game
    - once the other player's strategy has been revealed
    
- Nash equilibria are ***inherently stable***

:::

## Nash Equilibrium in the Stag Hunt?


<br>

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Stag</font></td>
<td align="center"><font size = 5px>Hare</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Stag</font></td>
<td align="center"><font color="#6666ff">3</font> , <font color="#ff4c4c">3</font></td>
<td align="center"><font color="#6666ff">0</font> , <font color="#ff4c4c">2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Hare</font></td>
<td align="center"><font color="#6666ff">2</font> , <font color="#ff4c4c">0</font></td>
<td align="center"><font color="#6666ff">1</font> , <font color="#ff4c4c">1</font></td>
</tr>
</table>
</center>


## Nash Equilibrium in the Stag Hunt?



<br>

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Stag</font></td>
<td align="center"><font size = 5px>Hare</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Stag</font></td>
<td align="center"><font color="#6666ff">3 </font> , <font color="#ff4c4c">3 </font></td>
<td align="center"><font color="#D3D3D3">0</font> , <font color="#D3D3D3">2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Hare</font></td>
<td align="center"><font color="#D3D3D3">2</font> , <font color="#D3D3D3">0</font></td>
<td align="center"><font color="#6666ff">1 </font> , <font color="#ff4c4c">1 </font></td>
</tr>
</table>
</center>

# Nash Equilibria in real life

## Nash Equilibria in real life



- Traffic
  - Traffic Lights
  - Driving on the Left/Right

<br>

- Other Examples?

## Nash Equilibria in real life - Traffic Lights



<br>
<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Car 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Go</font></td>
<td align="center"><font size = 5px>Stop</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Car 1</font></td>
<td align="center"><font size = 5px>Go</font></td>
<td align="center"><font color="#6666ff">-5</font> , <font color="#ff4c4c">-5</font></td>
<td align="center"><font color="#6666ff">1</font> , <font color="#ff4c4c">0</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Stop</font></td>
<td align="center"><font color="#6666ff">0</font> , <font color="#ff4c4c">1</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">-1</font></td>
</tr>
</table>
</center>

## Driving on the Left/Right

<iframe width="900" height="600" src="https://www.youtube.com/embed/q52RfAiZlws" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## A Beautiful Mind

<iframe width="900" height="500" src="https://www.youtube.com/embed/2d_dtTZQyUM?si=NEArdP966vWDkAb8" frameborder="0"allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Matching Pennies

## Matching Pennies{.smaller}

:::{.incremental}

- 2 players have a penny
- Each put penny down either Heads up or Tails up
- If both show heads or both show tails (they match) <font color="#6666ff">Player 1</font> wins
- If one shows heads and the other shows tails (they do not match) <font color="#ff4c4c">Player 2</font> wins

<br>

- Strictly competitive / *zero sum* game
- Players actively want the opponent to perform poorly


:::

## Matching Pennies



<br>

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Heads</font></td>
<td align="center"><font size = 5px>Tails</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Heads</font></td>
<td align="center"><font color="#6666ff">1</font> , <font color="#ff4c4c">-1</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">1</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Tails</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">1</font></td>
<td align="center"><font color="#6666ff">1</font> , <font color="#ff4c4c">-1</font></td>
</tr>
</table>
</center>

## Matching Pennies



No mutual best strategy - no pure strategy Nash equilibrium

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Heads</font></td>
<td align="center"><font size = 5px>Tails</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Heads</font></td>
<td align="center"><font color="#6666ff">1*</font> , <font color="#ff4c4c">-1</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">1*</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Tails</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">1*</font></td>
<td align="center"><font color="#6666ff">1*</font> , <font color="#ff4c4c">-1</font></td>
</tr>
</table>
</center>

## Matching Pennies and Nash Equilibrium{.smaller}

:::{.incremental}

- Every finite game has a Nash equilibrium in mixed strategies

- **Nash Existence Theorem**: If each player in an *n*-player game has a finite number of pure strategies, then the game has a (not necessarily unique) Nash equilibrium in (possibly) mixed strategies <br>[@gintis_game_2009, p. 44]

- If I could read your mind, how would you beat me at Matching Pennies?

- mixed strategy refers to how we are randomizing over multiple strategies (across multiple trials) rather than playing a single “pure” strategy. 

:::

## Mixed Strategy Nash Equilibrium



Flipping the coin (randomisation) gives each player an Expected Utility of .5

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Heads</font></td>
<td align="center"><font size = 5px>Tails</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Heads</font></td>
<td align="center"><font color="#6666ff">1*</font> , <font color="#ff4c4c">-1</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">1*</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Tails</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">1*</font></td>
<td align="center"><font color="#6666ff">1*</font> , <font color="#ff4c4c">-1</font></td>
</tr>
</table>
</center>


# Mixed Strategy Algorithm

## Mixed Strategy Algorithm



<br>

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Left</font></td>
<td align="center"><font size = 5px>Right</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Up</font></td>
<td align="center"><font color="#6666ff">3</font> , <font color="#ff4c4c">-3</font></td>
<td align="center"><font color="#6666ff">-2</font> , <font color="#ff4c4c">2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Down</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">1</font></td>
<td align="center"><font color="#6666ff">0</font> , <font color="#ff4c4c">0</font></td>
</tr>
</table>
</center>

## Mixed Strategy Algorithm



<br>

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Left</font></td>
<td align="center"><font size = 5px>Right</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Up</font></td>
<td align="center"><font color="#6666ff">3*</font> , <font color="#ff4c4c">-3</font></td>
<td align="center"><font color="#6666ff">-2</font> , <font color="#ff4c4c">2*</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Down</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">1*</font></td>
<td align="center"><font color="#6666ff">0*</font> , <font color="#ff4c4c">0</font></td>
</tr>
</table>
</center>

## Mixed Strategy Algorithm

:::{.incremental}

- In matching pennies, flipping against the mind reader was intended to make the Expected Utility of each of the opponents strategies the same
  - Calculate best strategy for <font color="#6666ff">Player 1</font>
      - $EU_L = EU_R$
  
- $EU_L = f(\sigma_u)$
- $EU_R = f(\sigma_u)$

- Express - $EU_L$ and $EU_R$ in terms of $\sigma_u$ and solve for $\sigma_u$

:::

## Mixed Strategy Algorithm



Expected Utility of Left

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Left</font></td>
<td align="center"><font size = 5px>Right</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Up</font></td>
<td align="center"><font color="#6666ff">3</font> , <font color="#ff4c4c">-3</font></td>
<td align="center"><font color="#6666ff">-2</font> , <font color="#ff4c4c">2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Down</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">1</font></td>
<td align="center"><font color="#6666ff">0</font> , <font color="#ff4c4c">0</font></td>
</tr>
</table>
</center>

- $EU_L$ is -3 sometimes (when <font color="#6666ff">Player 1</font> plays Up) and 1 the rest of the time

- $EU_L = \sigma_u(-3) + (1-\sigma_u)(1)$

## Mixed Strategy Algorithm



Expected Utility of Right

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Left</font></td>
<td align="center"><font size = 5px>Right</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Up</font></td>
<td align="center"><font color="#6666ff">3</font> , <font color="#ff4c4c">-3</font></td>
<td align="center"><font color="#6666ff">-2</font> , <font color="#ff4c4c">2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Down</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">1</font></td>
<td align="center"><font color="#6666ff">0</font> , <font color="#ff4c4c">0</font></td>
</tr>
</table>
</center>

- $EU_R$ is 2 sometimes (when <font color="#6666ff">Player 1</font> plays Up) and 0 the rest of the time 

- $EU_R = \sigma_u(2) + (1-\sigma_u)(0)$

## Mixed Strategy Algorithm{.smaller}

:::{.incremental}

- $$EU_L = EU_R$$

- $$\sigma_u(-3) + (1-\sigma_u)(1) = \sigma_u(2) + (1-\sigma_u)(0)$$

- $$-3\sigma_u + 1 - \sigma_u = 2\sigma_u + 0$$

- $$6\sigma_u = 1$$

- $$\sigma_u = \frac{1}{6}$$

- If <font color="#6666ff">Player 1</font> plays Up $\frac{1}{6}$ of time <font color="#ff4c4c">Player 2</font> is indifferent between Left and Right

:::

## Mixed Strategy Algorithm



- Calculate <font color="#ff4c4c">Player 2's</font> best strategy using the same calculation but letting 
  - $EU_u = f(\sigma_L)$
  - $EU_d = f(\sigma_L)$
- and solving for $\sigma_L$

- Yields $$\sigma_L = \frac{1}{3}$$

## Mixed Strategy Algorithm



Mixed Strategy Nash Equilibrium:

<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">Player 2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Left</font></td>
<td align="center"><font size = 5px>Right</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">Player 1</font></td>
<td align="center"><font size = 5px>Up</font></td>
<td align="center"><font color="#6666ff">3</font> , <font color="#ff4c4c">-3</font></td>
<td align="center"><font color="#6666ff">-2</font> , <font color="#ff4c4c">2</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>Down</font></td>
<td align="center"><font color="#6666ff">-1</font> , <font color="#ff4c4c">1</font></td>
<td align="center"><font color="#6666ff">0</font> , <font color="#ff4c4c">0</font></td>
</tr>
</table>
</center>
<br>

- $\sigma_u = \frac{1}{6} , \sigma_L = \frac{1}{3}$


# Number Beauty Contest

## Number Beauty Contest (Trial 1)

:::{.incremental}

- Everyone picks a number between $1$ and $100$

- Everyone's response is collated to [calculate the Mean](https://www.easycalculation.com/statistics/mean-median-mode.php)

- The Mean is multiplied by a constant $\frac{2}{3}$

- Congratulations if you picked the *most beautiful number*

:::

## Number Beauty Contest (Trial 1)



<iframe width="900" height="600" src="https://docs.google.com/spreadsheets/d/1e_1XbMqxMbQuUivtAu19kNlIumi4nPSN-TqOiurl5Ys/edit?embedded=true&rm=minimal" frameborder="0" ></iframe>





## Number Beauty Contest (Trial 2)



- Pick a number between $1$ and $100$

- [Calculate the Mean](https://www.easycalculation.com/statistics/mean-median-mode.php)

- The Mean is multiplied by a constant $\frac{2}{3}$

- Congratulations if you picked the *most beautiful number*

## Number Beauty Contest (Trial 2)



<iframe width="900" height="600" src="https://docs.google.com/spreadsheets/d/1e_1XbMqxMbQuUivtAu19kNlIumi4nPSN-TqOiurl5Ys/edit?embedded=true&rm=minimal" frameborder="0" ></iframe>



## Number Beauty Contest (Trial 3)


- Pick a number between $1$ and $100$

- [Calculate the Mean](https://www.easycalculation.com/statistics/mean-median-mode.php)

- The Mean is multiplied by a constant $\frac{2}{3}$

- Congratulations if you picked the *most beautiful number*


## Number Beauty Contest (Trial 3)

<iframe width="900" height="600" src="https://docs.google.com/spreadsheets/d/1e_1XbMqxMbQuUivtAu19kNlIumi4nPSN-TqOiurl5Ys/edit?embedded=true&rm=minimal" frameborder="0" ></iframe>



## Strategy for the Number Beauty Contest{.smaller}

:::{.incremental}

- Midpoint of $1$ and $100$ is $50$
  - Mean of uniformly drawn sample is $50$
  - $\frac{2}{3}$ of $50$ is $33.33 . . .$
- Best strategy is to guess around $33.33$ . . .   ? 

<br>

- Everyone guessing $~33$ brings the Mean closer to $33$
  - ***BUT***  $\frac{2}{3}$ of $33$ is $22.22 . . .$

- Best strategy to guess around $22$. . . ?<br><font size=4.5>[@keynes_general_1936; @dowling_modern_2007]</font size>

:::

# Ultimatum/Dictator Games

## Basic Ultimatum Game (Dictator Version 1){.smaller}

:::{.incremental}

- In pairs identify who is <font color="#6666ff">Player 1</font> and who is <font color="#ff4c4c">Player 2</font>

<br>

- <font color="#6666ff">Player 1</font> receives €100

- <font color="#6666ff">Player 1</font> may divide the €100 between you and <font color="#ff4c4c">Player 2</font> however you like.

- End of the Game

- What is the ***rational*** choice?

:::

## Basic Ultimatum Game (Dictator Version 2){.smaller}

:::{.incremental}

- In pairs identify who is <font color="#6666ff">Player 1</font> and who is <font color="#ff4c4c">Player 2</font>

<br>

- <font color="#6666ff">Player 1</font> receives €100

- <font color="#6666ff">Player 1</font> may divide the €100 between you and <font color="#ff4c4c">Player 2</font> however you like.

- <font color="#ff4c4c">Player 2</font> can accept or reject the offer

- End of the Game

- What is the ***rational*** choice?
  - for <font color="#6666ff">Player 1</font>
  - for <font color="#ff4c4c">Player 2</font>
 
:::
  
## Ultimatum Game{.smaller}

:::{.incremental}

- In pairs identify who is <font color="#6666ff">Player 1</font> and who is <font color="#ff4c4c">Player 2</font>

<br>

- <font color="#6666ff">Player 1</font> receives €100

- <font color="#6666ff">Player 1</font> may divide the €100 between you and <font color="#ff4c4c">Player 2</font> however you like.

- <font color="#ff4c4c">Player 2</font> can
  - accept the offer
  - reject the offer
      - If  <font color="#ff4c4c">Player 2</font> rejects, **both** players get **nothing**

- End of the Game

:::

## Ultimatum Game

:::{.incremental}

- What is the ***rational*** choice?
  - for <font color="#6666ff">Player 1</font>
  - for <font color="#ff4c4c">Player 2</font>
  
:::

## Fairness vs Rationality

<iframe width="900" height="600" src="https://www.youtube.com/embed/-KSryJXDpZo" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## Backward Induction

:::{.incremental}

- Sum of money to be divided between <font color="#ff4c4c">Ann</font> and <font color="#6666ff">Ben</font> 
- <font color="#ff4c4c">Ann</font> starts with 100p and can give some to <font color="#6666ff">Ben</font> 
- <font color="#6666ff">Ben</font> can accept or reject
  - if <font color="#6666ff">Ben</font> rejects:
      - Money is reduced to 25p and <font color="#6666ff">Ben</font>  is in charge of dividing the money
  
- <font color="#ff4c4c">Ann</font> can accept or reject
  - if <font color="#ff4c4c">Ann</font> rejects, both receive nothing

:::

## Backward Induction


<img src="resources/images/backward_induction.png" height="400px"  />

<font size=4.5>[taken from @dowling_modern_2007, p. 118]</font size>


## Backward Induction and the Centipede Game

:::{.incremental}

- A dime (10c) is put on the table
- <font color="#6666ff">Player 1</font> has the option to take it
- If <font color="#6666ff">Player 1</font> leaves it, another dime is placed on top and <font color="#ff4c4c">Player 2</font> has the option to take it
- If <font color="#6666ff">Player 2</font> leaves it another dime is added
  - and so on. . .

:::

## Backward Induction and the Centipede Game{.smaller}

:::{.incremental}

- Assume there are 10 rounds, this will leave $1 on the table at <font color="#ff4c4c">Player 2's</font> decision
  - Final round, <font color="#ff4c4c">Player 2</font> will take the money
- By backwards induction <font color="#6666ff">Player 1</font> should take at round 9
  - but <font color="#ff4c4c">Player 2</font> should anticipate this and take the money at round 8
      an so on. . .

- Nash Equilibrium is for <font color="#6666ff">Player 1</font> to take the dime on round 1
  - Without prior collusion participants have waited till the last round and split the money

:::

# The Prisoner Dilemma revisited

## Beyond Individual Games

:::{.incremental}

- Game theory works for investigating behvaiour at the individual level

<br>

- Can also be used to test the emergence of ***best*** or ***most robust*** strategies through computer simulations

<br>

- The effectiveness of strategies relative to each other can be established

:::

## Repeated Trials of the Prisoner Dilemma



- @axelrod_evolution_1984 famously simulated the Prisoner Dilemma using a points system

<br>
<center>
<table class = 'table-style-one'>
<col width="200px" />
<col width="200px" />
<col width="200px" />
<col width="200px"/>
<tr class="odd">
<td colspan = "2" rowspan = "2"></td>
<td colspan = "2" align="center"><font color="#ff4c4c">B</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>cooperate</font></td>
<td align="center"><font size = 5px>defect</font></td>
</tr>
<tr class="odd">
<td rowspan = "2" align = "center"><font color="#6666ff">A</font></td>
<td align="center"><font size = 5px>cooperate</font></td>
<td align="center"><font color="#6666ff">3</font> , <font color="#ff4c4c">3</font></td>
<td align="center"><font color="#6666ff">0</font> , <font color="#ff4c4c">5</font></td>
</tr>
<tr class="even">
<td align="center"><font size = 5px>defect</font></td>
<td align="center"><font color="#6666ff">5</font> , <font color="#ff4c4c">0</font></td>
<td align="center"><font color="#6666ff">1</font> , <font color="#ff4c4c">1</font></td>
</tr>
</table>
</center>
<br>

## Repeated Trials of the Prisoner Dilemma{.smaller}

:::{.incremental}

- A "tournament" for strategies was devised and the winner was ***Tit for Tat***
  - Initially offer cooperation
  - Respond to defection with defection
  - Observed during WW1

- @nowak_arithmetics_1995 used learning algorithms
  - cooperation eventually prevailed 
      - *generous tit for tat* (failed to retaliate occasionally)
      - *Pavlov*

:::

# In-Class Activity

## In Class Activity 



- In groups identify features of games discussed in everyday activities
- Pick an example of everyday activity that illustrates some of the concepts discussed today

# References

## References

\noindent
\vspace{-2em}
\setlength{\parindent}{-0.5in}
\setlength{\leftskip}{0.5in}
\setlength{\parskip}{7.5pt}

