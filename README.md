# myproject01: Mag 7

This is my first Lede project making a webpage. Myproject01 is a bout **the biggest shareholders of the Magnificient 7 companies**. I chose the topic because it is something I could create visualizations for at work, and also because I know the data provides an opportunity to practice data handling, or 'doing pandas.' The topic itself, the Mag 7 companies, is constantly relevant in the investment world, so it is also interesting to me.

### My datacollection for Mag7

I collected the data together with my Finnish colleague trough a **financial data provider Factset**. We use this regurlaly at work but I do not have access to Factset data service myself, and its licenses require employer approval. The information is pulled out as a excel file containging the information requested. Data was retrieved for each company separately by specifying how many shareholders were wanted on the list - in this case 20 - arranging them from largest to smallest. Each company’s Excel file contained rows of information that was unnecessary for me, such as the source of the reported information. I edited the data somewhat immediately after retrieval, even though I knew I wanted to do further filtering in Jupyter Notebooks using Pandas.

### My Pandas work for Mag 7

I started with the file *tablecleaning* in Jupyter Notebooks, but after quickly checking the number of rows and the heads of the tables, I noticed errors in the excell I had altered: the number of rows did not match the expectation of having a list of 20 owners for seven companies. After checking, I began working in a new notebook, *newtablecleaning*. In it, I corrected the heads of the tables and removed unnecessary columns. At this stage, I wanted to separate from the 20 largest owners of the Mag 7 companies those who are common to all. **My assumption was that there would be several common owners.** Additionally, I wanted to separate "natural persons" from institutional owners (banks, asset managers). **My assumption was that there would be very few individual owners among the largest owners.**

Since I had modified my data quite a bit in the notebook, I decided to start again with the original data. I wanted to *practice creating a bar chart based on the ownership percentage for the top 10 owners of each Mag7 company*. Finally, I downloaded all the dataframes I processed in the notebooks into Excel files. The idea is that I will eventually create visual presentations from them in Datawrapper and/or Illustrator. I had to do this two times since I had forgot MSFT and used wrong numbers in 4-6 dataframes!

## My visual work for Mag 7

I used **datawrapper and Illustrator** and I already can use them well. I wish I had more time to do an oppening picture for my story but it's done, it's fine as Soma says... 

## My HTML work for Mag 7

This part of the work was not so familiar for me so I used Soma's template and did some small tweeks. 

## My webpage for Mag 7

https://armyniemela.github.io/MAG7/
