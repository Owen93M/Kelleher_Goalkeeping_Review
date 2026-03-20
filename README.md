# Kelleher Goalkeeping Review

## Project Overview
* This project was created to look at the `goalkeeping abilities` of `Caoimhin Kelleher`. The attributes observered were:
    * Penalty Concedes & Saves - With Shot Locations
    * Saves & Save Percentages
    * Shots On Target & Goals Allowed
    * PSxG - Post Shot Expected Goals
    * Goal Kick AVG Length
    * Passing And Throwing
    * Distribution AVG Length

## Imports
<img width="384" height="137" alt="Image" src="https://github.com/user-attachments/assets/626cb2e4-082a-474b-ba3b-31c2eb2be4da" />

* Improrting all the libraries to `manipulate` the data and `create visualisations`.

## Opening And Reading Penalty Save Stats Data File
<img width="589" height="307" alt="Image" src="https://github.com/user-attachments/assets/131e787b-7c15-43e4-ac1d-b5a65972628e" />

* I uses `with open` to retrieve the file and named it using `as`, to simplify the code for later use.
* Using `csv_reader`, I read the file.
* Then I used a `For Loop` to put all the data into rows.
* I finally used `print` to show the rows.

## Creating A DataFrame
<img width="577" height="309" alt="Image" src="https://github.com/user-attachments/assets/3867504c-0979-4240-8308-bca64f69f456" />

* I created a variable that stored the data from the `kelleher_pen_saves` csv file. I then called the variable to show the DataFrame.

---------------

## Penalty Shot Locations
### Penalty Graph Code Part.1
<img width="741" height="660" alt="Image" src="https://github.com/user-attachments/assets/65294fcc-73eb-42c5-bfe4-af6edc4a634c" />

*

### Penalty Graph Code Part.2
<img width="567" height="792" alt="Image" src="https://github.com/user-attachments/assets/8e6ed99b-d560-46c5-83cf-762e1a0613bf" />

*

### Penalty Shot Locations Graph Output
<img width="875" height="456" alt="Image" src="https://github.com/user-attachments/assets/4d847216-721c-4cfa-b1d0-dcd5b257f3e2" />

* The ouput shows that Kelleher has quick reactions and judgement when the ball is low and or central.
* The least likely saves are made when the ball is placed at the side of the goal, a notoriously difficult save to make unless timed well.

------------

### Opening And Reading Overall Stats Data File
<img width="1405" height="526" alt="Image" src="https://github.com/user-attachments/assets/a80e6ad7-9856-4db3-a5b0-ea3fc329e8ae" />

* This code is the same as the `penalty saves file`, just with the file name changed to `kelleher_stats`.

### Creating A DataFrame
<img width="842" height="417" alt="Image" src="https://github.com/user-attachments/assets/df325821-330d-453c-87fb-1029721052a6" />

* This code also the same as the `penalty saves file`, just with the file name changed to `kelleher_stats`.

--------

## Saves & Percentages
### Saves & Percentages DataFrame
<img width="1405" height="674" alt="Image" src="https://github.com/user-attachments/assets/803c9e80-4da9-415e-8d7e-5bb91e4a4071" />

*

## Saves & Percentages Graph
### Saves & Percentages Graph Code
<img width="871" height="725" alt="Image" src="https://github.com/user-attachments/assets/3480b6b2-e77e-417d-bfcc-15dbe3bb66b3" />

*

### Saves & Percentages Graph Output
<img width="1023" height="706" alt="Image" src="https://github.com/user-attachments/assets/b0c8896a-34e4-4d57-a2ee-7176015a415f" />

* The graph shows that in the majority of the games analysed, Kelleher achieved  `50% or higher` only 1 match was `33.3%`.
* This shows that Kelleher has a reliablity to his game that gives defenders and the whole team confidence.

---------

## Shots On Target Allowed & Goals Allowed
### Shots On Target Allowed & Goals Allowed DataFrame
<img width="833" height="399" alt="Image" src="https://github.com/user-attachments/assets/775cd61b-3bd1-4211-b23e-82152ebe9592" />

*

## Shots On Target Allowed & Goals Allowed Graph
### Shots On Target Allowed & Goals Allowed Graph Code
<img width="829" height="731" alt="Image" src="https://github.com/user-attachments/assets/3691cd0e-0403-4345-a494-4fa1e7a14cce" />

*

### Shots On Target Allowed & Goals Allowed Graph Output
<img width="913" height="530" alt="Image" src="https://github.com/user-attachments/assets/9f4221c3-2ed5-4263-850a-a0156d50754e" />

* `8 goals` out of `38 shots on target` gives a save percentage of `79%`, adding to the reliability of his performances.

----------
## PSxG - Post Shot Expected Goal
### PSxG Code
<img width="362" height="295" alt="Image" src="https://github.com/user-attachments/assets/06bcea67-11e7-4b5c-a76a-f9997f7dba70" />

*

## PSxG Graph
### PSxG Graph Code
<img width="709" height="623" alt="Image" src="https://github.com/user-attachments/assets/4db6151a-eaf0-4866-bd70-76b6fb91cc95" />

*

### PSxG Graph Output
<img width="1017" height="699" alt="Image" src="https://github.com/user-attachments/assets/3e99e6bf-450e-4c66-acb2-a36ff3aa1733" />

* The graph show quite a few chances that had a `low chance` of resulting in a goal, to incrementally moving upwards over `1.0`, to reaching close to`2.0`. Theres was only 1 stand out of `2.5`. This shows that majority of saves that Kelleher made were dealt with proficently. 

--------------

## Goal Kick AVG Length
### Goal Kick AVG Length DataFrame
<img width="1381" height="656" alt="Image" src="https://github.com/user-attachments/assets/fbe3f4bd-85d3-411f-9a3b-6969992973cd" />

*

### Goal Kick AVG Length `mean()` Code
<img width="349" height="129" alt="Image" src="https://github.com/user-attachments/assets/3cb4ef34-69b4-4fa1-8d40-45d7fbef8d62" />

*

## Goal Kick AVG Length Graph
### Goal Kick AVG Length Graph Code
<img width="694" height="718" alt="Image" src="https://github.com/user-attachments/assets/d1f1306e-13fa-4bff-a748-3c312c120a90" />

*

### Goal Kick AVG Length Graph Output
<img width="716" height="644" alt="Image" src="https://github.com/user-attachments/assets/23053f32-9c19-44cb-9321-500447d8209b" />

* There are 2 talking points on this graph:
    * The 2 `lowest points`, indicate that the `opposition played deep` and `long passes werent optional`, so it forced play out from the back
    * The `highest point` indicates the opposite and that the team was pushed high up, so long passes were optional to get past the defensive line.

---------------

## Pass And Throw

## Pass And Throw Graph
### Pass And Throw Graph Code
<img width="842" height="747" alt="Image" src="https://github.com/user-attachments/assets/30b7e8b1-a9d2-48da-b87d-547aefe8a08b" />

*

### Pass And Throw Graph Output
<img width="920" height="526" alt="Image" src="https://github.com/user-attachments/assets/ce6fa4ab-e93f-4185-a1af-b0dc53b16dcf" />

* This graph shows that the option to `kick the ball` out rather than `throw` was more `favoured`, as this could be short goal kicks to CBs to build up play or that playing the ball back to keeper to recycle and/or draw in attacking players to play through press was the prefered play.

---------------

## Distribution AVG Length

## Distribution AVG Length Graph
### Distribution AVG Length Graph Code
<img width="712" height="607" alt="Image" src="https://github.com/user-attachments/assets/b75b913e-e1d4-41d4-a5aa-c804f41a648a" />

*

### Distribution AVG Length Output
<img width="716" height="636" alt="Image" src="https://github.com/user-attachments/assets/e5b762c8-804b-4b30-8ac1-2fe0f198f0d4" />

* Both the points again indicate the same as the other distance graph, that the lowest point, was due to the opposition playing deep and/or wanting to draw the opposition in to play through the press, and that the highest was due to opposition playing high and opening for long passes over the defensive line.
