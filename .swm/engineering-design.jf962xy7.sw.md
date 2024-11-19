---
title: Engineering design
---
## References

- Other relevant documents
- Link to PRD

## Goals

Main KPIs of this feature

## High level design

- {{Flow chart, like this one}}

```mermaid
sequenceDiagram
Service A->>+Service B: GET /objects/{id}

Service B-->>Service A: 200 OK (object)
Service A->>+Service C: GET /data/{object_internal_id}
Service C-->>Service A: 200 OK
```

- DB changes
- UI components
- What is stored (e.g., in the state, local storage...)

## Third party integrations

- Logs
- Analytics

## Tests to be added

## Migrations

## Security implications

## Roll-out plan

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBc21hcnQtbWlycm9yJTNBJTNBSWRpdFllZ2VyU3dpbW0=" repo-name="smart-mirror"><sup>Powered by [Swimm](https://staging.swimm.cloud/)</sup></SwmMeta>
