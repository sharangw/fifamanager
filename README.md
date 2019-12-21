# fifamanager
A Flask web application for football player replacements
This application implements the FIFA 19 dataset analysis done in here: https://github.com/sharangw/fifa-data-analysis

It is hosted on Azure: https://fifa-manager.azurewebsites.net

First, you enter the name of a player that you wish to get possible replacements of. This will search the FIFA data for player names similar to the one entered. Next, you must select the actual player from the list of similar-sounding names.

Once you hit search, it uses cosine-similarity and KNN to find and display the five other players closest to the original in terms of skills and other attributes.
