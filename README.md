# Ponies
## Introduction
This repository will mainly serve as a place to apply fundamental data science techniques to a not-so-basic horse racing dataset. The goal is mainly to learn and practice statistical learning strategies rather than making headway on an existing horse racing project. However, if some progress is made on that front I won't complain (and will probably make a TVG account).

## Dataset Overview
 - horse_id: Unique identifier of a horse.
 - race_id: Unique identifier of a race. Each (race_id, horse_id) combination will have 1 or more past races associated with it.
 - rating: The rating the horse achieved in the current race. This is the value I wish to predict utilizing past race information.
 - surface: Surface of the current race.
 - distance: Distance of the current race.
 - date_diff: Days between the current race and the previous race.
 - prev_surface: Surface of the previous race.
 - prev_distance: Distance of the previous race.
 - prev_rating: The rating the horse achieved in the previous race.
 - prev_race_rating: The rating of the previous race. Think of this as a race quality measure.
 - place_rating: A measure aimed at quantifying a horse's average position throughout the previous race. A higher number suggests a horse was more forwardly placed. 
 - movement_rating: A measure aimed at quantifying a horse's movement throughout the race. A lower number (counterintuitively) suggests a horse progressed forward through the field during the race.
 - odds_perc: The horse's share of the public betting pool in the previous race.
 - place: The horse's place in the previous race.
 - nh: The number of horses in the previous race.
 - r: The index of a horse's previous races. 1 = the horses last race, 2 = the horses second to last race, etc.