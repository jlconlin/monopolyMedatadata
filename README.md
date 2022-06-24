# monopolyMedatadata
Metadata in JSON for monopoly

## Terminology
I've invented a bit of terminology in order to develop the code for this game.

- `space` This is just a space on the board. It does nothing, but it knows what tile occupies that space and it knows who it's immediate neighbors are.
- `tile` A tile is what occupies the space.
- `property` A property is a tile that can be owned by a player
- `neighborhood` This is a group of properties that, when all owned by a single player, gives that player additional benefits.

## Contributions
I freely borrowed (i.e., stole) the meta data for the game from [@danielstern](https://github.com/danielstern/science/blob/master/monopoly.json). I've taken his JSON file and manipulated it the way that I wanted it to look. Thanks to @danielstern for doing the hard work.

## LICENSE
This is distributed according to the [LICENSE](LICENSE).
