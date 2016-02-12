# mapCrap
Drawing maps with Python to answer questions.

## Current high-level question

**What part of London can I reach by public transport in 30 minutes starting in different places?**

Public transport is great - but how to make it greater? One way is to make better connections, so that the people who don't love it so much can spend less time using it. That means better connections and the first thing is to investigate, how well the current system is connected. Assuming - for a given region - that all the tube, bus and other stops are equally easy to get to, what fraction of London can one reach within a fixed period of time. Are some region underconnected?

### Addressing the high-level question (the high-level plan)

1. Draw a map of London and divide it into regions. Boroughs are probably too rough, but maybe not
2. Overplot all the public transport stops and find which region, borough or other, they belong to.
3. Find all the lines that service those stops and see how far you can get using those lines.
4. Allow for changes.

