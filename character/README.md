@"
# Character Query by ID

This project contains GraphQL queries and their JSON outputs for retrieving specific character details using the `character(id: ID!)` field.

**Endpoint:**  
https://rickandmortyapi.com/graphql

**Fields retrieved:**
- id
- name
- status
- species
- type
- gender

**Files:**
- `character-id-1.graphql` → Query for character ID 1
- `character-id-1-output.json` → Output for character ID 1
- (Similarly for IDs 2, 3, and 4)
"@ | Set-Content README.md