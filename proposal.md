# Project proposal 
(unfortunately this is simultaneously verbose and incomplete)

**Research question: (depends on which approach I go with)**

**idea 1, structure came frmo a chatbot :/**
One of the chatbot-suggested research designs I found was something along the lines of "make a contingency table regarding two different variables from WALS; use glottolog to group the languages by family or region." This option has the advantage of being concrete, I could merge WALS and glottolog data on the ISO-639-3 id's that are given in both resources, and I could have a clear research question. 

If I do that approach, I would pick two language features[^1] as variables. I'd compare how much they overlap, and then I'd map it out, and group languages using region or family info frmo glottolog. 

Then my main goals would be learning how to get the data (from Newick, or PhyloXML, or SVG Classification Trees... I don't know what those are but of course I'd be learning that). Then I'd need to merge and collect the data in a meaningful way, and then I'd need to visualize it (perhaps with bar charts and a map). So I would also be working with a new visualization library - Bokeh, maybe, or geopandas. 

---
**idea 2**

The other idea was more vague and involved plotting languages on a map and counting languages per region, or maybe comparing number of official languages to number of languages spoken in a region. The issue is that neither glottolog nor WALS really contain a spread of where an individual language is spoken - just a single lat/long point of reference for sort of where the origin of that language is. So I then would need to find my data somewhere else and start with a new idea.

---
While I don't love using the chatbot for 'inspiration,' the first one is the clearest project design I have, so that's the best I can suggest at this point (and it's already quite late).


[^1]:The meaning of "language feature" is hard to explain without showing it, but an example of a language feature is "basic word order" as defined by Subject, Object, and Verb, and it can be a number of options: SOV, SVO... etc. Another feature would be something like "does this language put possessives before or after the noun." Those aren't the two features I'd necessarily pick, but that's an example of comparisons that could be made in a table: how many languages of each word order (SOV, SVO, etc.) has a specified genitive(possessive) order (before Noun, after Noun, no order).
