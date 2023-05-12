<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/GraphQL_Logo.svg/512px-GraphQL_Logo.svg.png" width="100" alt="graphql logo"/>
<img src="https://i.imgur.com/migo24P.png" width="100" alt="moon highway logo"/>
</p>

# GraphQL Workshop

Welcome! We're really glad you're here! Below you'll find all of the resources that we'll use throughout this course. If you're looking for slides, samples, links, etc., this is the place to look.

## Instructor Info

- **Eve Porcello**: [Twitter](https://twitter.com/eveporcello) | [Email](mailto:eve@moonhighway.com)
- **Moon Highway Training**: [Moon Highway Website](https://www.moonhighway.com) | [Mailing List](http://bit.ly/moonhighway) | [Articles](https://www.moonhighway.com/articles)

## GraphQL Query Language

- [Query Language Slides](https://slides.com/moonhighway/graphql-intro/)
- [GitHub GraphQL Explorer](https://developer.github.com/v4/explorer/)
- [Pet Library](https://pet-library.moonhighway.com)
- [Funded Pet Library](https://funded-pet-library.moonhighway.com)
- [Snowtooth Playground](https://snowtooth.moonhighway.com)
- [Lab Instructions](https://slides.com/moonhighway/snowtooth-query-lab/)

## GraphQL Schemas

- [Schema Slides](https://slides.com/moonhighway/schema-definition-language)
- [Schema Cheatsheet](https://raw.githubusercontent.com/sogko/graphql-shorthand-notation-cheat-sheet/master/graphql-shorthand-notation-cheat-sheet.png)
- [Starting Repo](https://github.com/MoonHighway/pet-library-schema)
- [First Schema Iteration](https://github.com/MoonHighway/pet-library-schema/tree/initial-schema)
- [Complete Schema](https://github.com/MoonHighway/pet-library-schema/tree/complete)
- [Unions & Interfaces](https://slides.com/moonhighway/apollo-schema-design-advanced)

_Don't want to work with the repo or code editor? Use the [Schema Project in CodeSandbox](https://codesandbox.io/s/github/moonhighway/pet-library-schema)_

### Federation

- [Federation](https://www.apollographql.com/docs/federation/)
- [Pet Schema](https://github.com/MoonHighway/federated-mock-pets-sample)
- [Customer Schema](https://github.com/MoonHighway/federated-customers-mock-sample)

## GraphQL Clients

### Simple Requests

- curl Request

```sh
curl -X POST \
     -H "Content-Type: application/json" \
     --data '{ "query": "{allLifts{name}}" }' \
     http://snowtooth.moonhighway.com
```

- [Fetch Sample](https://codesandbox.io/s/n3jro0o4n0)
- [graphql-request](https://codesandbox.io/s/4qzq5z2vz0)
- [Snowtooth UI Start Files](https://github.com/graphqlworkshop/snowtooth-ui)

### Apollo Link - Creating a Network Layer

- [Apollo Client](https://codesandbox.io/s/adoring-architecture-uw413f?file=/src/index.js)
- [Concatenating Links](https://codesandbox.io/s/ql4jlz54yq)

### Apollo & React

- [Snowtooth UI Start Files](https://github.com/graphqlworkshop/snowtooth-ui)
- [Snowtooth UI Finished Files](https://github.com/graphqlworkshop/snowtooth-ui/tree/complete)

### Client Documentation

- [Apollo Client Docs - React](https://www.apollographql.com/docs/react)
- [Apollo Client Docs - iOS](https://www.apollographql.com/docs/ios)
- [Apollo Client Docs - Kotlin](https://www.apollographql.com/docs/kotlin)
- [Persisted Queries](https://www.apollographql.com/docs/apollo-server/performance/apq/)
- [Relay Docs](https://relay.dev/)
- [Relay Connection Spec](https://relay.dev/graphql/connections.htm)

### Caching

- [Caching Slides](https://slides.com/moonhighway/client-cache-config/)
- [Caching, Client Side Schema](https://github.com/eveporcello/pet-library-client)

### Defer and Stream

- [Defer and Stream Slides](https://slides.com/moonhighway/defer-stream)
- [Defer in Apollo Client](https://www.apollographql.com/docs/react/data/defer/)
- [Defer Demo](https://studio.apollographql.com/public/hack-the-e-commerce/explorer?variant=main)
