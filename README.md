# GraphQL-server

Create a new npm project with npm init and install the required dependencies.

```npm install @apollo/server graphqlcopy```
Also create a index.js file in your project's root directory.

The heart of the code is an ApolloServer, which is given two parameters:

const server = new ApolloServer({
  typeDefs,
  resolvers,
})
