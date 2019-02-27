# Memory

Memory (also known as Concentration) is a card game played with one or more players. Using a standard card deck (including both jokers) the players shuffle the deck and lay all of the cards face down on a surface and two cards are flipped face up over each turn. The object of the game is to turn over pairs of matching cards. Concentration can be played with any number of players or as solitaire. [Wikipedia](<https://en.wikipedia.org/wiki/Concentration_(game)>) has a good description of the game.

Your challenge is to build Memory in the browser with the requirements below.

## Guidelines

### Setting Up

1. Clone this repository
2. Change the remote to a private github repository under your username
3. Push code to that remote
4. Develop

### To Submit

1. Add github user `znicholasbrown` as a collaborator to your private repository

### The Game

Using the provided deck in `data/deck.js`:

1. Shuffle the deck
2. Display all 54 cards (jokers included) face down
3. Clicking the back of a card should turn a card over
4. Player can turn over 2 cards at a time
5. When two cards are turned over:
   - if the **number** and **color** of the cards match, the player collects the pair and the cards are removed from the board
   - if the cards **do not** match, they turn back over and **remain in position**
6. When a player has found all 27 pairs, the player should see a success message

### Requirements

1. One player can play one entire game
2. Sensible tests (see [@vue/test-utils](https://vue-test-utils.vuejs.org/guides/#common-tips))
3. Clear commit messages & history
4. Well-styled & readible cards

Note: I've given you a Vue app skeleton. If you wish, you can implement this with another framework (or no framework at all). If you choose to do this, please retain the `src/deck.js` file.

### Bonus Points

1. Animations for card flips
2. Snapshot tests
3. Mobile & tablet friendly
4. Deploy App & add deployment instructions to README
5. Reset Button that starts an in-progess game over from the beginning
6. Track the score
7. Multiple player support

## Resources

- [Vue docs](https://vuejs.org/v2/guide/)
- [Vue Test Utils docs](https://vue-test-utils.vuejs.org/)
- [Jest docs](https://jestjs.io/)
- [Game description](<https://en.wikipedia.org/wiki/Concentration_(game)>)

## Project setup

```bash
nvm install
npm install
```

### Compiles and hot-reloads for development

```bash
npm run serve
```

### Compiles and minifies for production

```bash
npm run build
```

### Run your tests

```bash
npm run test
```

### Lints and fixes files

```bash
npm run lint
```

### Run your unit tests

```bash
npm run test:unit
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
