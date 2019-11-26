# Design Graphql Schemas Workshop

## Intro

```
GraphQL brings joy to using APIs. Even though it's based on a type system, GraphQL in many ways is more flexible than REST.

Even though it's based on a type system, in many ways GraphQL is more flexible than REST.

But the flexibility that makes GraphQL a joy to work with can have its downsides if you aren't careful.

Schema design is an area where one small oversight at the beginning can get you stuck having to deal with weird naming, bloated duplicates, and other annoying workarounds.

It doesn't have to be like this!

Nik Graf has extensive experience designing GraphQL schemas, for a variety of business applications.

In this workshop, Nik has prepared several examples following different design patterns. Through exploration and comparison, you'll come away from this workshop with actionable knowledge for designing and extending schemas.

Follow Nik, and avoid making Schema mistakes that will come back to bite you later.

This live remote workshop will be held on November 11, 2019 at 10:30 am - 1:30 pm Pacific​

Workshop Topics Include:

Naming conventions for fields, queries, mutations
GraphQL Aliases
Benefits of nullable fields and when to use them
Connection Specification and why you want to use it
Extending connections to attach relationship metadata
Extending connections to build pagination UI
Mutation Payload Design
Handling expected errors for Mutations
GraphQL RFCs e.g. Datetime, Union Input Types
```

## Setup

```
yarn install # or npm install
yarn start
```

In `index.js` you can change the imports to import the respective lesson.

Visit `http://localhost:4000` to see GraphiQL.

## How it works

For every lesson there is a folder. It includes a README.md with notes. Some of them contain an exercise at the end of the lesson.

Process for every lesson:

1. Presentation by Nik
2. Q&A
3. Exercise (not every lesson has one)
4. Break

## Lessons

1. Setup
2. Design Process
3. Naming Fields
4. Aliases and how they impact naming
5. Nullable Fields
6. Connections incl. Cursors
7. Extending Connections
8. Naming Queries
9. Node Interface
10. Mutation Payload
11. Expected Errors in the Mutation Payload
12. Naming and structuring Mutations
13. Union Input RFC
14. Datetime RFC
