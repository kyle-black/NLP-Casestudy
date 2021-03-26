# NLP-Casestudy


### Object
- Find clustering of first hand accounts of Bigfoot sightings.

### RAW DATA
- We imported the Bigfoot data file. Within the JSON we found dictionaries that included,  _id,  URL,  HTML, and time. We focused our energy on the HTML dictionary key values, which contained first hand accounts of Big Foot sightings.

### Text Processing

-In order to parse out our data we used Beautiful soup’s HTML parser to find ‘p’ within the content in order to separate the starts and stops of the paragraphs.
  
-This left us with 4405 observed accounts.  
   
- Snowball : We used to get words to their roots.
- Wordnet to connect words using their synonyms and homonyms
  
 ![alt text](https://github.com/kyle-black/NLP-Casestudy/blob/main/Screen%20Shot%202021-03-26%20at%205.28.58%20PM.png)
 
 
 ###  ML Algorithms
  -K Means clustering to find clustering among words in sightings
  
  
  - In 8 clusters we found the top features for each clusters:
  # 0: tree, deer, trail, heard, area, like, woods, hunting, just, truck
  # 1: tracks, prints, print, inches, snow, foot, track, toes, footprints, area
  # 2: road, saw, driving, car, creature, tall, looked, just, hair, like
  # 3: house, window, door, outside, heard, like, night, went, dog, dogs
  # 4: tent, camp, heard, night, camping, like, sound, went, got, just
  # 5: heard, sound, like, sounds, loud, scream, sounded, howl, night, woods
  # 6: river, water, fishing, boat, heard, saw, like, just, bank, area
  # 7: saw, creature, like, looked, tall, feet, woods, seen, just, large 
  
  
  
  ![alt text](https://github.com/kyle-black/NLP-Casestudy/blob/main/hierachical_tree.jpg)
  
  #  Top  20 Most Common Words
  
  [('like', 6591),
 ('back', 6463),
 ('heard', 6240),
 ('saw', 5259),
 ('could', 4946),
 ('road', 4646),
 ('see', 4468),
 ('one', 4429),
 ('around', 4323),
 ('area', 4276),
 ('time', 4117),
 ('us', 4063),
 ('would', 3888),
 ('something', 3611),
 ('woods', 3479),
 ('looked', 3398),
 ('went', 3368),
 ('got', 3288),
 ('feet', 3200),
 ('night', 3099)]

  
 
 
  
