A Node.js + Mongoose + Jest sample project that demonstrates **how to test mongoose operations using Jest with an in-memory database**.



# Dependencies
What you need to run this project:
- Node.js

(MongoDB is not required because it'll run in memory, handled by the package `mongodb-memory-server`).

# Try it out
## 1. Install dependencies
```
npm install
```

## 2. Run tests
```
npm test
```

# Contribute
Feel free to contribute to this project either by leaving your comments and suggestions in the Issues section or creating a PR. More and diverse test examples are always useful. Make sure to take a look at Jest docs and the existent examples to avoid repeating.

# Tools
Main tools used in this project:

- [Mongoose](https://mongoosejs.com/)
- [Jest](https://jestjs.io/)
- [mongodb-memory-server package by @nodkz](https://github.com/nodkz/mongodb-memory-server)

> Also take a look at [mongodb-memory-server-global](https://github.com/nodkz/mongodb-memory-server#mongodb-memory-server-global) to download mongod's binary globally and [mongodb-memory-server-core](https://github.com/nodkz/mongodb-memory-server#mongodb-memory-server-core) if you'll run the test on a server that already has mongod installed.
