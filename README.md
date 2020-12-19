# Generate Title By Plot
Movie title generation by plot

For this project we used dataset with movie plots and titles from Kaggle.\
As a model we used new Google transformer T5 model from HuggingFace library (`t5-base`)

Result files are in in `data/predictions.csv` file\
You can see some examples below


***Plot:*** When a dysfunctional family gathers for Thanksgiving at their New England home, past demons reveal themselves
as one son returns for the first time in three years.\
***Actual Title:*** The Myth of Fingerprints\
***Generated Title:*** The demons

***Plot:*** Alvin Roberts (Lee Tracy) feuds with Bunny Harmon (Dick Powell), a singer. Roberts reports on society people 
who are expecting, i.e. going to have a child. One such report antagonizes a gangster in a delicate situation, who 
sends over a henchman to threaten him. Roberts manages to turn the tables on the gangster.\
***Actual Title:*** Blessed Event\
***Generated Title:*** Alvin roberts

***Plot:*** In 1898 the US government decided to intervene on the side of the Cuban rebels in their struggle against 
Spanish rule. Assistant Navy Secretary Theodore Roosevelt decides to experience the war first hand by promoting and 
joining a volunteer cavalry regiment.
The regiment, later known as the Rough Riders, brings together volunteers from all corners of the nation and all 
walks of life. They include a stagecoach robber, Henry Nash, and patrician men.
When Roosevelt and his men finally land on Cuba, they face ambush, intense enemy fire, and a desperate, outnumbered 
charge up a defended hill.\
***Actual Title:*** Rough Riders\
***Generated Title:*** The rough riders