#Open History Database

## What is the Open History Database?

It's all in the name:

### Open

+ Any one can contribute to the project
+ Both the source-code and the data that the code produces is open
  + The derivative data is provided under [the Creative Commons CC0 License](https://creativecommons.org/about/cc0/)
  + The source-code used to scrape, shape and serve the data is provided under [The MIT License](https://opensource.org/licenses/MIT)

### History

The word "history", in this project, means a factual account (evidence-based) of humanity's past.  It involves:

+ **Events** that have happened.  These can be long or short, for example: The Stone Age; the formation of planet Earth; World War I; The Battle of the Somme; The Moon Landing; Lighbulb Invented.
+ **People**, who could be alive or dead, such as Srinivasa Ramanujan, Winston Churchill, David Bowie, Shaka Zulu, and Queen Elizabeth I.
+ **Places**.  They can be entire regions such as Great Britain, or very specific locations, such as St Paul's Cathedral.  The places may not exist today, for example: The Kingdom of Leon or The Persian Empire.
+ **Things**: the objects of the past.  They could be specific things, such as Vincent van Gogh's *The Starry Night*, or general things such as the *Panzerkampfwagen Tiger Ausf. B* or the compass.
+ **Ideas** that have spread through the world, such as religions, renaissance philosophy, exploration, feudalism, and so forth.

For more details, have a look at [Data Model].

There are a number of things that, for this project, the term "history" does not mean:

+ **The interpretation of history**.  Let's stick to the agreed-upon facts.
+ **Legendary tales** and **myth**, such as Santa Claus, the tale of Ragnarr Loðbrok, the legend of King Arthur, and other such events, places, and people for which there is no compelling evidence.

### Database

+ The data is modelled as described in [Data Model]
+ An API should be built to allow for easy machine-driven addition, modification and cleaning of the data (see [Goals])

## Why build an Open History Database?

+ It's fun to build things
+ It's interesting to learn more about the past
+ It serves as an educational tool to anyone interested in the history of our species
+ So that better things can be built on top of it

## Goals

1. **Use existing knowledge bases.**  To reduce conflicting information and duplication of effort, existing sources of data, such as Wikipedia and Wikidata should be used.
2. **Keep the data tody.**  [Tidy data][http://vita.had.co.nz/papers/tidy-data.pdf] = happy data!
3. **Build an API**  Once implemented, anybody could contribute to the data, and individual tweaks are a must-have feature.  However, when dealing with data as big (potentially) as the whole of human history, machines are useful in scraping, shaping, analysing and posting vast amounts of data.  To this end, a friendly API should be built.
4. **Present in visual and interactive manner** Having a vast quantity of historical data is one thing, but if human users aren't able to view, explore and interact with the data, then there is no point.  The project should provide some means of doing so.

## Data Model

<TODO>

## Contributing

+ Anyone can add data to the system (once implemented)
+ Anyone can contribute code

## Legal

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="www.openhistorydatabase.org">
    <span property="dct:title">Bradley Marques</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">Open History Database</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="ZA" about="www.openhistorydatabase.org">
  South Africa</span>.
</p>