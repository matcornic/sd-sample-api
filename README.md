# sd-sample-api

1. Install json-server `npm install -g json-server`
2. Run `json-server --watch db.json`
3. Go to `http://localhost:3000/` and see resources

You can get all players with an HTTP GET on `http://localhost:3000/players`
You can get a player stats with an HTTP GET on `http://localhost:3000/stats?playerId=<player 'id'>` or `http://localhost:3000/stats/<player 'statId'>`  

You can change the player stats by editing the `db.json` file for your tests