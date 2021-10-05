---
layout: post
title: Project One 558
---
## Project One Overview  
For project one, I chose to work with the pokemon the [Pokemon API](https://pokeapi.co/) using [Pokemon API Documentation](https://pokeapi.co/docs/v2).  

My project one github pages repo is at [](https://github.com/mfaustin/ProjectOne558)  

My project one repo is at TBD  

With all the tough times we've had the last year and a half, I decided to go with the pokemon API because it seemed more light hearted.  I had a big learning curve though because I'd never played or read much about pokemon before this project.  

Thankfully the github parts of the assignment worked as expected without problems.  

I spent a few days just going through the pokemon documentation and learning what kind of data the API returns.  I also learned just enough about pokemon to understand the data.  I focused first on endpoints that appeared to have data that I could later use for analysis.  

For the query parts, I decided to add extra functions that return endpoint metadata.  I figured users would need to have a programmatic way to know the possible values for a given endpoint.  I also added different functions for returning data for one endpoint value and for returning data for all endpoint values.  

Given that I did some extra functionality, I decided to limit my query functions to 5 endpoints to meet the total query work requirement.  

I also decided to try different ways of letting users select the data returned.  For some endpoints, I created groups of data the users could select.  For other endpoints, the users can select any combination of data.  I wanted to get more practice with different approaches.  

Thankfully the variables I chose and created ahead of time worked well for the analysis parts.  I was surprised to see how often the graphs showed interesting findings and sometimes one finding would lead to the next idea.  


## Interesting Findings  

The most interesting finding to me was the 0.93 correlation between total points and base experience.  I expected these to be correlated because total points is a measure of a pokemon's total power and base experience is the reward given when that pokemon is defeated.  I had not expected the correlation to be that strong.  

In addition, the same variables had a really interesting scatter plot pattern with several lines with similar slopes.  That outcome led to the interesting question of what might explain the different lines?  



## What was the most difficult part of the logic and programming for you?  

The most difficult and very time consuming part for me was figuring out how to deal with the complex list of lists that the pokemon API returns.  I'd estimate up to 80% of my work for this project was working on the query functions due to the complexity of the data and my lack of prior experience with the needed tasks.  



## What would you do differently in approaching a similar project in the future?  

In the future, I would try to apply more efficient coding than I was able to implement.  A day before the project was originally due, I started seeing discussion board posts about using rcurl and purr to query the data.  I recognized that those methods would likely be more efficient.  However, for project one I did not have time in my schedule to try that approach out and did not want to risk breaking my working code right before the project was due.  

The other improvement I would make if I were starting over would be to do something like a wrapper function for some of what I coded since much of the code ended up being similar between functions.  


## Conclusion  

Before this project, the only API query I'd done was in the class homework.  I learned a lot about using R to interact with APIs and feel like I've still got more I could learn and apply in the future.  The hardest parts where the query and data wrangling parts.  The most fun and interesting parts where the data analysis section.  


