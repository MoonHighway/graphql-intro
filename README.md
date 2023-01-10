<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/GraphQL_Logo.svg/512px-GraphQL_Logo.svg.png" width="100" alt="graphql logo"/>
<img src="https://i.imgur.com/migo24P.png" width="100" alt="moon highway logo"/>
</p>

# GraphQL Workshop

Welcome! We're really glad you're here! Below you'll find all of the resources that we'll use throughout this course. If you're looking for slides, samples, links, etc., this is the place to look.

## Instructor Info

- **Eve Porcello**: [Twitter](https://twitter.com/eveporcello) | [Email](mailto:eve@moonhighway.com)
- **Moon Highway Training**: [Moon Highway Website](https://www.moonhighway.com) | [Mailing List](http://bit.ly/moonhighway) | [Articles](https://www.moonhighway.com/articles)


### GraphQL Query Language

- [Query Language Slides](https://slides.com/moonhighway/graphql-intro/)
- [GitHub GraphQL Explorer](https://developer.github.com/v4/explorer/)
- [Apollo Studio Link](https://studio.apollographql.com/sandbox/explorer)
- [Pet Library Playground](https://pet-library.moonhighway.com)
- [Snowtooth Playground](https://snowtooth.moonhighway.com)
- [Lab Instructions](https://slides.com/moonhighway/snowtooth-query-lab/)

### Schema Slides

* [Schema Slides](https://slides.com/moonhighway/schema-definition-language)
* [Schema Cheatsheet](https://raw.githubusercontent.com/sogko/graphql-shorthand-notation-cheat-sheet/master/graphql-shorthand-notation-cheat-sheet.png)

### Apollo Client

#### Simple Requests

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

#### Apollo Link Examples

- [HTTP Link](https://codesandbox.io/s/koj24j5l07)
- [Concatenating Links](https://codesandbox.io/s/ql4jlz54yq)
- [Apollo Client](https://codesandbox.io/s/oo3z008kzy?file=/src/index.js](https://codesandbox.io/s/adoring-architecture-uw413f?file=/src/index.js)

### Apollo & React

- [Snowtooth UI Start Files](https://github.com/graphqlworkshop/snowtooth-ui)
- [Snowtooth UI Finished Files](https://github.com/graphqlworkshop/snowtooth-ui/tree/complete)

### Caching

- [Caching, Client Side Schema](https://github.com/eveporcello/pet-library-client)

### Defer and Stream

- [Defer and Stream Slides](https://slides.com/moonhighway/defer-stream)
- [Defer in Apollo Client](https://www.apollographql.com/docs/react/data/defer/)
- [Defer Demo](https://studio.apollographql.com/public/hack-the-e-commerce/explorer?variant=main)
