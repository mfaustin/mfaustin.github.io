---
layout: post
title: Project Two 558
---
## Project Two Overview  
I worked on project two with Maks as my partner.  

Our project two github pages project is at [https://mfaustin.github.io/ProjectTwo558/](https://mfaustin.github.io/ProjectTwo558/)

Our project two github repo is at [https://github.com/mfaustin/ProjectTwo558](https://github.com/mfaustin/ProjectTwo558)    

The project asked us to analyze [an online new popularity data set](UCI Machine Learning Repository: Online News Popularity Data Set) using both regression and tree based ensemble methods.  We needed to produce channel specific output for each of the 6 channels.  The output markdown files needed to be generated using rmarkdown automation.  All the data and modeling was done in one .RMD file and rendered with one .R script into the various channel specific markdown output files.

Per requirements, we added channel specific automation of model comparison leading to winning model specific to each channel.  We also added automation to the Introduction section and the document title to give each channel more channel specificity.    

 
## What would you do differently?  

Once we started fitting the ensemble models, I ran into a lot of issues related to runtime.  Using parallel computing helped some but runtimes were still pretty long for all channels combined.  If I were starting over, I would use my newer laptop which has more memory to help deal with some of the runtime issues.



## What was the most difficult part for you?  

I was the one who developed our rmarkdown automation coding for the documents.  The render code wasn’t too hard to implement but the details within the .RMD code were more challenging.  In particular, I realized the way we were saving images needed to change because we were using only one directory.  The one directory approach led to image files being overwritten.  I fixed that issue by adding conditional logic to define a different image directory for each channel.

Later we turned on cache functionality to speed up reruns of longer running models.  I needed to add channel specific directories for the cache too within the existing conditional logic.

One neat new idea I learned was that YAML title can be dynamic based on a document variable.  In order to make that happen, the YAML title needs to be listed after the variable has the needed value.    


## What are your big take-aways from this project? 

Project two added working with a partner.  This showed how important some coordination can be when working on the same files in github.  We developed a rhythm of working at different times so that we rarely needed to merge.  I’m used to pushing smaller changes which also helped because when merges did occur they were manageable.

My approach to software development has been to do the harder parts first when possible.  This helped out with the markdown automation since we had a really smooth finish where I’d seen about the automation early.

Finally, I learned a lot more about the practical side of both automation and fitting models with larger data and all the details involved.  With software there are always details that are best learned by experience.  In this case I learned about dealing with runtime performance and how to work within computing limits.
