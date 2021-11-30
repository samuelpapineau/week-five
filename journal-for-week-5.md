---
week:
date: 2021-11-29
tags: tag1, tag2, etc
---

# Introduction 

## Resonances
"Because flawed classification systems—like the one that underlies the airport scanner’s risk-detection algorithm or the one that determines which names end up on terrorist watch lists or simply (simply!) the gender binary—are not only significant problems in themselves, but also symptoms of a more global condition of inequality."  (*Data Feminism* by Catherine D’Ignazio and Lauren Klein)

I like this quote, because it summarized my thought process during the collection process, and it was further amplified by my work for this week. Suppose one mistake is made during the collection process, it will then snowball into an even bigger problem and contaminate the properly recorded data from other sources. It is bigger than just a global condition of inequality, but a spread of global misinformation, where we need to carefully check any data we get for errors.

"In many ways, the movement for open access, defined as free of charge and free of many copyright and licensing restrictions, conceptualized by Suber ([Reference Suber2012](https://www.cambridge.org/core/journals/advances-in-archaeological-practice/article/teaching-open-science-published-data-and-digital-literacy-in-archaeology-classrooms/8404682E019727CCF43416B81E4E9092#ref041):4) as the barrier-free revolution, is perfectly suited to the demands of higher education."

I also very much appreciate this quote because it is truer than most people believe. The digital world would not have been developed so quickly had all software been proprietary and heavily commercialized.


## Response to the Prompts

For this week, it was time to grab the data we had collected in order to visualize and manipulate it to be able to use it in further research. But first, there are several questions that needed to be answered. How good was the quality of the data? Could it efficiently be used in other research? Were there any mistakes made? Any information left out? How does this data affect the families of the people who have been recorded? These questions were greatly discussed in *What gets counted, counts*, a chapter from *Data Feminism* by Catherine D’Ignazio and Lauren Klein. In this chapter it is discussed how the inefficiency of modern data collection processes create a lack of information which can negatively affect certain people, and can fail to produce accurate data in the long run. This is very similar to what I had seen previously with the KoBoToolbox form, where grave features were greatly generalized, and I often found myself having a hard time trying to accurately represent the gravestone. I thought to myself during the collection process: "How is this information supposed to be accurate, if there's no fields in the form for me to add in some of these features?" and it would appear other people thought so as well.

I first went through the excercises by level of ease as mentioned in the Week 5 notes. I began by creating an account on KoBoToolbox and I imported the form which was used for recording the graves, without any issues. Then, when it came to modifying the form, I decided add several "other" fields to many of the questions. I did this because I remembered in the beginning of the *Data Feminism* chapter, on how Facebook was praised for allowing users to simply type what gender they were, instead of choosing from multiple options. I decided I wanted to add this to the form, and I added an extra text field near the end for any additional information which was specifically not lsited on the forms. I know there was a similar text field there already, but I interpreted it as a field for any features that may have been specific only to that gravestone, and not features which could be found across several. This new text field will allow for future researchers to modify the form by adding commonly found features which aren't currently listed.


For the basic stats in R portion, I had successfully completed the excercises with some experimentation along the way. Due to having coded before, it was only a matter of learning the proper syntax of R and learning about which variables I needed to use where. 

![[images-week-5/Michelsberg type 4 bottles.png]]
*A bar chart representing type 4 bottles counts from the Michelsberg database.*

<br>
The only real difficulty I had was that I was unable to find any associations using the Chi squared method, though I now understand how it works.

![[images-week-5/Chi-squared test.png]]


As per the final excercise in R, I experimented with the Graveyard Project database and created some rather dense graphs.

![[images-week-5/graves_bar.png]]
![[images-week-5/graves_circ.png]]
*I suppose one problem with having a large amount of data is that it is rather difficult to represent visually...*

<br>
Lastly I read through the database sections in the Jupyter notebooks and got stuck in importing the Graveyard Project database, so I unfortunately was not able to try it out with the SQL commands, though I have used MySQL and SQLite in the past so I'm a little confused as to why it didn't work. From my past experience though, I have previously been stuck on SQL problems for several days, so I decided it would probably be a good idea to skip the rest of this section due to limited time.
