## Checkpoint 4 DA Final Project -> Creating A Tableau Story

I spent somewhere between 50 - 60 hours on this project.  It is not perfect, there are plenty of things I would like to continue to work on.

**Tips for success:**
* Don’t try to do it all in one weekend
* Save often!!  
* I had problems saving my story -> solution was to add each dashboard to my story seperately and save before adding the next one -> still had to try several times when adding some dashboards, Tableau would freeze and may or may not let me cancel, if not I’d have to force quit and reopen from the saved copy online.
* Again save often, and spread the work out over many days and weeks.


**Research On Creating a story:**

[Creating Executive Style Tableau Presentations](https://www.youtube.com/watch?v=JsDxcEH5VeA)  
[Shading & Backgrounds in Tableau Part 2: Dashboards – graphhopper](https://graphhopperblog.wordpress.com/2019/10/17/shading-backgrounds-in-tableau-part-2-dashboards/#:~:text=From%20the%20Dashboard%20menu%2C%20go,on%20top%20of%20the%20dashboard)


## Outline:

### Cover Page
From Bean to Bar:
What goes into making the best chocolate bars in the world?

**Photo Credit:**  
Great site for royalty free images -> must include a link to give credit  
https://www.vecteezy.com/photo/2636184-chocolate-and-cocoa-beans-with-cocoa-on-a-black-background  
[How to add a hyperlink in tableau](https://www.thedataschool.co.uk/paul-hunt/insert-a-hyperlink)


### Introduction

By analyzing the [Chocolate Bar 2020](https://www.kaggle.com/soroushghaderi/chocolate-bar-2020) database we were able to gain insight and a broader understanding of what goes into making a superb bar, from beans to ingredients to flavor profiles that rank the best. And what ranks the worst in order to avoid.
Graph -> Map with average rating from each country -> province of beans 

[Maps and Geographic Data Analysis in Tableau](https://help.tableau.com/current/pro/desktop/en-us/maps.htm)
[Get Started Mapping with Tableau](https://help.tableau.com/current/pro/desktop/en-us/buildexamples_maps.htm)
[Dashboard with interaction between two sheets](https://community.tableau.com/s/question/0D54T00000C5k9gSAB/dashboard-with-interaction-between-two-sheets)


Fixing Map -> 5 unknown values

![Fixing Unkown Values in Tableau](https://github.com/codinglikeagirl42/Checkpoint4FP/blob/main/Fixing%20Unkowns%20CP4.png)  
1. Click on the unknown.  2. I choose Edit Locations and a new pop up window opens as seen below.

![Editing Locations Manually in Tableau](https://github.com/codinglikeagirl42/Checkpoint4FP/blob/main/Edit%20Location%20Checkpoint%204.png)
I looked up each missing location and manually entered them, leaving just one -> 
Blend and I added a note with Avg Rating which I caculated in a seperate goole worksheet.  


### Bar Ingredients

Average Bar rating based on ingredients used -> can filter by # of ingredients


### Taste profiles

First Taste -> Second Taste -> Third Taste


### The Fourth Taste

How does this affect the rating?

### Conclusion

Word cloud of all the tastes represtended -> combined count of all four tastes
Link to github repo.

[Word Clouds in Tableau: Quick & Easy.](https://towardsdatascience.com/word-clouds-in-tableau-quick-easy-e71519cf507a)  
[Create your own color palette in tableau public.](https://www.reddit.com/r/tableau/comments/mvinug/creating_custom_color_palette_in_tableau_public/)  
[TPS File Extension - What is it? How to open a TPS file?](https://filext.com/file-extension/TPS)  
[I used coolors.co to design the palette and get the hex codes.](https://coolors.co/palette/f6e0e4-d6bd91-ce6716-fef8ef-94480f-f59623-5e1c29-ecddfd-4d089b-93394a)  
[Color Palettes for Tableau](https://public.tableau.com/app/profile/datavizard/viz/ColorPalettesforTableau/color)


In C:\Users\{your username}\Documents\My Tableau Repository 
edit the Preferences.tps file -> open in RStudio

Insert your code between `<workbook> </workbook>`

Example:

```
<workbook>
    <preferences>
        <color-palette name="ChocolateLight" type = "ordered-sequential">
            <color>#ECC0C8</color>
            <color>#D6BD91</color>
            <color>#CE6716</color>
            <color>#FEF8EF</color>
            <color>#94480F</color>
            <color>#F59623</color>
            <color>#9d2f45</color>
            <color>#ECDDFD</color>
            <color>#4D089B</color>
            <color>#93394A</color>
        </color-palette>
    </preferences>
</workbook>
```



**Additional Research:**

Parameters:

[Parameters | Oh, the places you'll go!](https://www.youtube.com/watch?v=Xk9HnpmWtsU)  
[Tableau Deep Dive: Parameters - Filtering Across Data Sources - InterWorks](https://interworks.com/blog/rcurtis/2016/06/02/tableau-deep-dive-parameters-filtering-across-data-sources/#:~:text=Remember%2C%20filters%20are%20different%20than,data%20source%2C%20parameters%20are%20not.&text=Parameters%20can%20be%20reused%20across,filter%20across%20different%20data%20sources)






