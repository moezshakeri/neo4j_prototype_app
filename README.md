# neo4j_prototype_app

A Flutter GraphQL / Neo4j prototype project.

### Important points

- This prototype using a graphQL server on `http://localhost:4000`, you can change it in `lib/Helper/graphql_helper.dart`.
- I used `graphql` package to connect and create a graphQL Client.
- The `lib/Helper/graphql_helper.dart` class is a simple helper to create and return a graphQL client on each call. you can refactor it as a `Service` in your application.
- Check `lib/screens/home_screen.dart` to see how we send requests and receive data.