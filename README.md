# NLP-Casestudy


### RAW DATA
- We imported the Bigfoot data file. Within the JSON we found dictionaries that included,  _id, # URL,  HTML, and time. We focused our energy on the HTML dictionary key values, which contained first hand accounts of Big Foot sightings.

### Text Processing

 -In order to parse out our data we used Beautiful soup’s HTML parser to find ‘p’ within the content in order to separate the starts and stops of the paragraphs.
  
 -This left us with 4405 observed accounts.  
  
 - Porter Stemmer: We used to get words to their roots.
 - Snowball : 
 - Wordnet to connect words using their synonyms and homonyms
  
  
 
 
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
  
  
  
  
 
  
