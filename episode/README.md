## Fetch Episode Details by ID

This GraphQL query fetches details of a specific episode using its ID.

### Query file

- `episode-page-1.graphql`

### Query structure

```graphql
query {
  episode(id: "1") {
    id
    name
    air_date
    episode
  }
}