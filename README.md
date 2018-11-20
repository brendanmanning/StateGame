# StateGame
Guess the state (with a twist!) Figure out the answer to the trivia question, then select the correct state on tha map!
# Installation
StateGame is played in the browser, but is managed by a Nodejs server. Therefore, we need to setup a webserver and a game server. Please follow the steps below, in that order.

## Game Server Setup
1. Run `git clone https://github.com/brendanmanning/StateGame.git && cd StateGame && cd Server`
2. Install dependencies `npm install`
3. Start server `forever start index.js`

## Web Client Setup
1. Download and unzip on server
2. Move contents of `Web/` to webroot (usually `/var/www/html/`)
3. Edit `Web/config.js` to http://(your game server URL):3000

## Play
1. Open http://(your web server address) in your browser to play
2. Create new game
3. Share link with friends ;)
4. **Note:** Chrome users will have to "Load Unsafe Scripts" as GitHub Pages forces HTTPS, which is not supported by StateGame server.
