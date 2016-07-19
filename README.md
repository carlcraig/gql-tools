# gql-tools
This package provides several command-line tools to work with GraphQL schemas. For instance, generating the
introspected schema or the schema AST in JSON format.

### Installation
Install *gqltools* locally and add as dependency to the current project.

```sh
npm install --save gql-tools
```

Install *gqltools* globally.

```sh
npm install -g gql-tools
```

**Note**: this package requires *graphql* as peer dependency.

```sh
npm install [-g] graphql
```

### Usage
* **gqlschema**: generates the introspected schema and the schema AST of a given GraphQL schema language.
  * **usage**: *gqlschema  <schema.txt>*
