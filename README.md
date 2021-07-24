# baseless.bingo
All of the bingo, none of the research. Baseless bingo is a bingo sheet randomiser for the podcast Baseless Speculation built with Jekyll and Pure CSS for minimal web bloat.


## Contribution
New episode of Baseless Speculation with new potential bingo sheets come out weekly. You can add any missing bingo sheets by forking this repo and submitting a pull request with your new sheet randomiser. All sheets are placed in "src/_posts" and are formated in markdown with YAML headers.

The sheet randomisers are formatted as follows:
```Markdown
---
title: "Movie Title"
layout: bingo
eplink: Link to BS episode on acast
freesq: free center square
squares:
    - Each
    - other
    - bingo
    - square
---
Description of movie (can just be taken from IMDB).
```
A full sheet requires 24 squares and 1 free square.

## Support
If you would like to support this project both this repo and the website support Brave rewards tipping. So, if you are using the Brave browser (which you should be) you can send a BAT tip.

## To-Do
* Write guides for installing and contributing so anyone can assist development or run an instance.
* Add back catalog of episodes
* Add sorting system for sheet randomisers
* Add search system for sheet randomisers
* Add more detail and content to index and about pages