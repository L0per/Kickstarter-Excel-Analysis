# Kickstarter Excel Analysis
Simple analysis of ~4000 Kickstarter projects using Excel.

1. **Given the provided data, what are *four* conclusions we can draw about Kickstarter campaigns?**

   - Kickstarter projects launched in February through May had the greatest probability of meeting funding goals. Successful funding   drops through the year and bottoms in December. This may be due to potential backers using their disposable income on holiday-related items:
   
   ![](https://github.com/L0per/Kickstarter-Excel-Analysis/blob/master/Readme_Images/Launch_Dates.png)
 
   - Kickstarter projects in the music category had the highest percentage of successfully funded campaigns:
   
   ![](https://github.com/L0per/Kickstarter-Excel-Analysis/blob/master/Readme_Images/Categories.png)
   
   - Staff picked projects had a greatly increased probability of meeting funding goals.
     - Only 48% of non-staff picked projects met funding goals, while 87% of staff picked projects met funding goals.
     
   ![](https://github.com/L0per/Kickstarter-Excel-Analysis/blob/master/Readme_Images/Staff_Picks.png)
     
     - Campaigns in the film & video, music, photography, technology, and theater categories were the most staff picked. However, the probability of being staff picked was greatest in the film & video category.
       - Documentaries in particular were chosen as staff picks, though they were successful whether or not they were staff picked.
       
   ![](https://github.com/L0per/Kickstarter-Excel-Analysis/blob/master/Readme_Images/Staff_Picks_Movies.png)
   
   - Kickstarter projects were more likely to be successfully funded if their funding goal was under $6000.
   
   ![](https://github.com/L0per/Kickstarter-Excel-Analysis/blob/master/Readme_Images/Funding.png)
 
2. **What are some limitations of this dataset?**

   - Based on stats from the Kickstarter website, there have been ~460k launched projects, so our sample is less than 1% of the population. This is also apparent by categories that do not appear in this dataset, but exist on the Kickstarter site.

   - There could have been additional variables captured:
     - Number of comments with timestamps.
     - Number of project updates with timestamps.
     - The length of the project page.
     - The amount of media on the project page – videos, pictures, links to other sites, etc.

3. **What are some other possible tables and/or graphs that we could create?**
 
   - This is demonstrated in my examples for staff picks and funding goals above.
   - Plots showing regression of percent funded vs different variables. I tried this for a few but did not find any significant results.
   - Coming from a Kickstarter revenue perspective, it would be interesting to look at which projects consistently met successful funding at higher goal amounts. Using my funding goal chart above, you can filter by different categories to narrow this down.
   - Clustered pie charts using different variables for successfully funded campaigns would also be interesting.

4. **Bonus: Funding Goal and Results**

   - The probability of reaching successful funding declines as the funding goal becomes greater.
   
   ![](https://github.com/L0per/Kickstarter-Excel-Analysis/blob/master/Readme_Images/Bonus.png)

 


