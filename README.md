# Environment variables
RIOT_API_KEY = Riot api key

# Simple example
```js
import { RiotApi } from 'riot-games-api'
import { Regions } from 'riot-games-api/constants'

const api = new RiotApi()

export async function summonerByNameExample () {
  return await api.leagueOfLegends.summoner.getByName('Hide on bush', Regions.KOREA)
}
```
[https://github.com/Sansossio/riot-games-api/tree/master/example](More examples)

# Run all examples
## Simple
```sh npm run example```

## Specific examples
```sh npm run example --example={exampleFunctionName}```

## With docker
Edit docker-compose.yml with your api key and:
```sh docker-compose up```