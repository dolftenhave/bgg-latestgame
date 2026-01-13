# BGG latest game

This program reads your last n recently played games from [boardgamegeek](https://boardgamegeek.com/) and compiles them into an image.

## TODO

- [] Get access to the [bgg api](https://boardgamegeek.com/wiki/page/BGG_XML_API2)
    - [golang bgg api?](https://github.com/fzerorubigd/gobgg)
- [] Parse the data and get cover images and date for each game played.
- [] Merge them into a single image that is output to the root dir.
- [] Automate the process to check for updates every n time/day.
