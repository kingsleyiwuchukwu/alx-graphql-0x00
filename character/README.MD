# ALX GraphQL Project 0x00

## Task: Get Character by ID

This project demonstrates how to fetch a specific character using a GraphQL query.

### Endpoint
https://rickandmortyapi.com/graphql


### Queries
We used the `character(id: ID!)` query with IDs **1, 2, 3, and 4**.

### Files
- `character-id-1.graphql` → Query for character with ID 1  
- `character-id-1-output.json` → Result of the query  
- `character-id-2.graphql` → Query for character with ID 2  
- `character-id-2-output.json` → Result of the query  
- `character-id-3.graphql` → Query for character with ID 3  
- `character-id-3-output.json` → Result of the query  
- `character-id-4.graphql` → Query for character with ID 4  
- `character-id-4-output.json` → Result of the query  

### Example Query
```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}

### Example Output
{
  "data": {
    "character": {
      "id": "1",
      "name": "Rick Sanchez",
      "status": "Alive",
      "species": "Human",
      "type": "",
      "gender": "Male"
    }
  }
}


