# World Cup Analysis: Data sets overview

All the information was collected from Wikipedia and FIFA sites:
- https://www.fifa.com/
- https://en.wikipedia.org/wiki/2018_FIFA_World_Cup
- https://en.wikipedia.org/wiki/2014_FIFA_World_Cup
- https://en.wikipedia.org/wiki/2010_FIFA_World_Cup
- https://en.wikipedia.org/wiki/2006_FIFA_World_Cup
- https://en.wikipedia.org/wiki/2002_FIFA_World_Cup
- https://en.wikipedia.org/wiki/1998_FIFA_World_Cup
- https://en.wikipedia.org/wiki/1994_FIFA_World_Cup
- https://en.wikipedia.org/wiki/1990_FIFA_World_Cup
- https://en.wikipedia.org/wiki/1986_FIFA_World_Cup
- https://en.wikipedia.org/wiki/1982_FIFA_World_Cup
- https://en.wikipedia.org/wiki/1978_FIFA_World_Cup
- https://en.wikipedia.org/wiki/1974_FIFA_World_Cup
- https://en.wikipedia.org/wiki/1970_FIFA_World_Cup
- https://en.wikipedia.org/wiki/1966_FIFA_World_Cup
- https://en.wikipedia.org/wiki/1962_FIFA_World_Cup
- https://en.wikipedia.org/wiki/1958_FIFA_World_Cup
- https://en.wikipedia.org/wiki/1954_FIFA_World_Cup
- https://en.wikipedia.org/wiki/1950_FIFA_World_Cup
- https://en.wikipedia.org/wiki/1938_FIFA_World_Cup
- https://en.wikipedia.org/wiki/1934_FIFA_World_Cup
- https://en.wikipedia.org/wiki/1930_FIFA_World_Cup


For the World Cup score goals analysis, there are two data sets: 
- the **historic_world_cup_goals** contains the number of goals and matches of all FIFA World Cups until 2018;
- the **qatar_world_cup_goals** contains the number of goals and matches of the FIFA World Cup Qatar 2022.

Both data sets have the same columns:

- year (int) - the year of the FIFA World Cup;
- world_cup_day (int) - the day of the FIFA World Cup. For example, the FIFA World Cup Russia 2018 opening match took place on June 14th and that is the world_cup_day 1.
- number_of_goals (int) - number of scored goals on that World Cup day. **Penalties shoot-outs goals after the extra times were not included**.
- number_of_matches (int) - number of matches on that World Cup day. **Group stage play-off matches were included**.
- cummulative_number_of_goals (float) - cumulative number of scored goals during the World Cup.
- cummulative_number_of_matches (float) - cumulative number of matches during the World Cup
- average_scored_goals (float) - average score goals during the World Cup. 

The data sets are available on my GitHub at: https://github.com/hanada-stephan/fifa_world_cup_analysis .  
Feel free to reach out on [Linkedin](https://www.linkedin.com/in/stephan-hanada/) for corrections, questions, and feedback.
