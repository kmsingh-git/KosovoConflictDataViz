# Visualizing Migrations and Killings data from the Kosovo conflict in 1999.

This visualization is to explore the spatial distribution of migrations, killings, NATO Airstrikes and KLA clashes during March - June 1999, across different regions of Kosovo.

I calculated 4 different summary statistics per region, for each of 28 municipalities in the Kosovo region (the 29th region was missing longitude and latitude vaues), and the user can click on each dot to reveal the statistics corresponding to that region.

## Instructions:
The user can first choose a Terrain/ Watercolor Rendering. This is simply to provide different perspectives of the Kosovo region.

Then, the user can click on individual points and that will display the relevant data for that region under the Summary Statistics region. For instance, if you click on the dot at (Long 20.05, Lat 42.55), you will see that it is Municipality 2, it had 30115 Migrations during the specified time, etc.

Finally, the user can choose which criterion is used to scale the size of dots. For any given criterion, say Migrations, the size of dot of the ith region, corresponds to the relative value of that criterion, compared to other regions. So if you observe Municipality 24 (Long 20.5, Lat 42.57), and the Migrations criterion is selected, the size of its dot will be relatively larger than other dots, because the number of Migrants from this region was relatively higher than that of other regions.

## Analysis:
Through this visualization, you can observe some big picture spatial trends for important statistics, namely Number of Migrations, Killings, NATO Airstrikes and KLA clashes.

The first observation one can make is that Most of the affected population was concentrated between Long (20, 21) and Lat (42.4, 43), since the sizes of dotes outside this range are relatively much smaller, no matter which criterion you use. This could be because of strategic reasons, perhaps this sub-region was more central in political or military importance than others. However, it could simply be because this was more densely populated than the remaining regions. To further this analysis, population data can be collected, and Relative Statistics can be collected, such as Migrations/ Populations for a given Municipality.

To narrow down on individual criterion, we see that the NATO Airstrikes were very selective in choosing Municipalities, for example Muni 19 had 54 out of about 350 Air Strikes. This could be because KLA had the strongest level of presence in that region. And this is something that can be verified by looking at the KLA activity criterion, and noting that there were 75 (out of 525 total) reports of KLA activity in Muni 19. Similarly Municipalities 2, 17, 20 had high relative values of KLA activity as well as NATO air strikes. This gives some credence to the observation that NATO Air Strikes were strongly correlated with reports of KLA Activity.

Moving on to Killings and Migrations, one would expect that there would be strong correlations between Number of Killings and Migrations for a given region. However we note that this doesn't come across from this visualization. For instance, Muni 20 had almost double the number of migrants compared to Muni 16, but about half the number of killings. This seems counter-intuitive, but the way our group rationalized it was to note that there must have been many itra-region migrations as well, from one Municipality to another more peaceful one, for instance. And would be no border record for these internal displacements. So the next step for this analysis would be to investigate this internal displacement data, depending on whether Municipalities were able to record them.
