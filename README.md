# Pymaceuticals

There was an odd problem I had with this dataset.



After merging the two files we had I noticed my resulting dataframe has a count of 250 mice rather than the 249 stated in the documentation for the homework.

After poring through the individual csv files and my resulting data I cannot find the mouse that caused this shift. I know from the resulting data that it was a female mouse treated with Propriva but I cannot find which one it may be as there are seemingly no outliers amongst this population.

Had it changed the entirety of the data or shown up alongside the other duplicate I would consider it invalid and remove it from the Dataframe. Yet, from all the observations I've made it seems to be a valid set of data so I've elected to keep it in for the assignment currently.

Perhaps it arose from my initial method of merging the dataframes and presenting unique mice? My assumption was that each mouse would have a 0 timepoint for their testing, and while I cannot find one without one, I do wonder whether this spawned another mouse out of thin air and my method could be improved.

Either way, despite my confusions with the presented data I did end up accurately presenting said data so for that much I am thankful.
