# StateGame
Guess the state (with a twist!) Figure out the answer to the trivia question, then select the correct state on tha map!
# Installation
StateGame is played in the browser, but is managed by a Nodejs server. Therefore, we need to setup a webserver and a game server. Please follow the steps below, in that order.

## Game Server Setup
1. Run `git clone https://github.com/brendanmanning/StateGame.git && cd StateGame && cd Server`
2. Install dependencies `npm install`
3. Start server `forever start index.js`

## Web Client Setup
1. For this repo on GitHub
2. Go to Settings on your forked repo
3. Enable GitHub pages (master branch)
4. Edit `Web/config.js` to http://(your game server URL):3000
5. Your WebClient is now hosted for free by GitHub :)

## Play
1. Open http://(your github pages address) in your browser to play
2. Create new game
3. Share link with friends ;)
