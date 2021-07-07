# ETL Project for 'Zelda: Breath of the Wild'

Team Malicious_Mongoose: Ronald Canepa, Drew Henning, Zaira Coronado, and Annie DeRossi

## Diving further into our Project 1 Data to make you the best Zelda Player you can be!


      
        Now, this is a story all about how
        our Data got flipped, turned upside down.
        We'd like to take a minute just sit right there,
        we'll show you how to become a Master of Hyrule, we swear.

        In the Shrine of Resurection, where you are raised
        You wake up from your nap feeling confused and dazed.
        Run around, smash things, finding your tools 
        Open up the doors, go explore Hyrule.

        Find a Cooking Pot, where you can make food,
        It'll help you build your strength and fortitude.
        Don't get in a fight without ingredients paired,
        Because you wouldn't want the Mosters to think you were scared.

        Elixirs in your bag, equiped with your spear,
        You're ready to roam Eldin and explore far and near.
        You're dressed head to toe in your armor that is rare,
        Ganon better be ready, because he won't have a prayer!

        Go to Hyrule Castle with your Bow of Light,
        Be sure to check your Armour and be ready to fight.
        Go save the Kingdom, because you are prepared.
        Now you can beat Ganon without any cares!  
    


        

## Data Clean up and Analysis

First we had to establish where we would find the information we needed to continue with this project. These are the two sources we used.

* [Airtable](https://airtable.com/shrI71ZROtt0PXTtr/tblnUrS3N0llbwoE3/viwfDkyLV42qRcIto)
* [Zelda Wiki](https://zelda.fandom.com/wiki/The_Legend_of_Zelda:_Breath_of_the_Wild)

We revisited the Airtable site in order to begin our table creation and the Zelda Wiki page to scrape supplemental information from the web.


## Transforming the Data

Secondly, we thought that transforming the Airtable data was a seemingly simple task until we ran into what was essentially three tables layered on top of each other. The apporach taken here was to separate the information into new tables with corresponding columns of data that matched each table subject. In order to do this we had to clean up the CSV version of the data before loading into SQL to create the tables we wanted.

The Zelda Wiki page was chosen to augment the information that we already had. In order to be sure we weren't reusing any information that had previously been presented we perfomed an elegent scraping of the web site to pull a few new categories of info, including a full list of Monsters that you will face in the game as well as a list of regions that can be visited throughout your stay in Hyrule.

## Loading our New Data

Finally, we decided that the best way to showcase our new data would be by using Jupyter Notebook and SQL. These two products provided us with a clear and concise way to present our findings. SQL makes it fairly easy for the player to search for a specific item in the database where Jupyter Notebook presents multiple items in an easy to read dataframe. We thought these two would be both user friendly as well as in depth enough for even the most experienced player to have all the data they could need at their fingertips.

