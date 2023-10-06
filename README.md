# World-happiness
  The dataset is gotten from Kaggle and it covers from year 2015 to year 2023. 
I started cleaning the data using excel by formatting column names, fields and observations to clean unnecessary values in the dataset. I also added columns to some tables that had missing fields such as Region and Happiness rank field, this was achieved using xlookup to find the corresponding field for each observation from the happiness index table. 
    Some tables did not have all fields listed below and inorder to use sql to merge all tables into one I included the missing fields with zero as values.
Using sql and selecting all fields listed below, I merged all tables from year 2015 -2023 into one.The dataset was cleaned and formatted using excel spreadsheets and sql - [view sql queries here](https://github.com/SEYI-FASE/World-happiness/files/12834465/World.happiness.2015.-.2023.txt) ,[view excel file here](https://github.com/SEYI-FASE/World-happiness/files/12834531/Complete.world.record.xlsx).

Exploration, findings and visualizations were derived using tableau
Interaction with visualization and overview can be viewed - [Visualizations](https://public.tableau.com/views/Worldhappinessrecords-2015-2023/Happiessscoresandranks?:language=en-US&:display_count=n&:origin=viz_share_link)

Checking through the dataset, I have picked the relevant columns that will be needed for this study which are:
* Year
* Country
* Region
* Happiness Rank
* Happiness Score
* Economy (GDP per Capita)
* Family
*	Health (Life Expectancy)
*	Freedom
*	Social Support
*	Trust (Government Corruption)
* Generosity
* Dystopia Residual
  
![World Happiness Records (2015 - 2023)](https://github.com/SEYI-FASE/World-happiness/assets/134503256/2edea213-dbb7-461c-bfbe-e92097eda63d)
