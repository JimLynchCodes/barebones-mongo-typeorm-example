# barebones-mongo-typeorm-example


First, install typeorm globally
```
npm i -g typeorm
```

Then install project dependencies
```
npm i
```

Try generating an initial migration
```
./node_modules/.bin/ts-node ./node_modules/typeorm/cli.js migration:generate -n initial
```

^ (note that this doesn't actually create any migration file 😢)


Then try changing the data model (src/entity/User.ts) and re-run the 


^ (note that this doesn't actually create any migration file 😢)


## Scaffoldinging
Created with the typeorm init command specifying mongo:
```
typeorm init --database=mongodb
```