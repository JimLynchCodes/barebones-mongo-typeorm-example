# barebones-mongo-typeorm-example

This project is meant to be an as-simple-as-possible project demonstrating the usage of typeorm for generating mongodb migrations based on the typeorm entities (in this case, the User entitity located in `src/entities/User.ts`).

Sadly, nothing happens when I run the "generate" typeorm migration command so really this project is for debugging this issue.


## Usage

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
