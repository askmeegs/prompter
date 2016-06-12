# prompter

(Notes)

**goal:** to work with open datasets/corpora to create a writer's prompt machine that
goes beyond traditional online "prompts" - more of a mood board generator. Want to mimic
the experience of walking into a museum exhibit, and allow the writer to tell a story about that.

Target audiences: people of all ages, writers, artists, etc.

The alpha version will be random-generated (choosing a random set of audio/textual/visual sources,
  getting random resources, and embedding them in the results page), but the end goal will be to allow
  not only for random generation, but also for user parameters including:
  - Search tokens, eg. *butterfly, secret agent, thunderstorm*
  - Geographic areas, eg. *New York City, Pyrenees, Shinjuku*
  - Resource type parameters: eg. *-type:audio_only*  
  - Time period parameters, by year

Prospective datasets:
- London natural history museum specimens http://data.nhm.ac.uk/dataset
- Tate Gallery JSON data
- Google Maps random location / street view
- [to be continued]
