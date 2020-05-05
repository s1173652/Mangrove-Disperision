# Mangrove-Dispersion
Dr. D Project
In this there are several scratch work files, this includes: BriScratch, BrookeScratch, SamMangroveScratch.

In these files is different trial and errors that we wen through while working on this data. BriScratch and BrookeScratch are very similar in terms of the statistics that is in them. You will find a boostrap for a nested zone and tide in BriScratch. SamMangroveScratch has a couple of extra tests that were run. There is a chi squared, also there are some tests on whether or not the propagule landed in a viable recovery place.

In the Mangrove Dispersion file, you will find the extent of what we did with the data. The data is not normal and therefore we ran a Kruskall Wallis test comparing distance traveled by zone. We also ran a Mann-Whitney test for distance traveled by tide and distance traveled by density. We ran descriptives on completely nested data, meaning zone 1 high tide high density and so on. Afetr doing this, we realized that there were not enough propagules in each treatmnent to bootstrap. So, we bootstrapped for distance traveled by zone, by tide, and by density (individually) and we saw a lot of the same results from the Kruskal Wallis and Mann-Whitney tests. We then looked at the descriptives for data nested by zone and tide (disregarding density). We bootstrapped for the nested data and saw there were some significant differences. 

There is a file called Organized data, which is the excel file we got our data from. We then reworked this data for certain portions of the code, the reworked data is called Propagule Data.
