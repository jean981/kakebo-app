### 📋 Description
This requirement defines the visualization of imported financial data,
providing dynamic filters, pagination, and a web interface built with Thymeleaf.

---

### 🎯 Objective
Deliver a clear and efficient user experience for financial data analysis.

---

### ⚔️ Features
- Dynamic filters
- Paginated results
- Optimized queries
- User-friendly UI

---

- ## Fluxo de Interação

```mermaid
sequenceDiagram
    participant U as  User
    participant UI as Thymeleaf
    participant C as Controller
    participant S as Service
    participant R as Repository
    participant DB as DataBase

    U->>UI: Access /efaturas
    UI->>C: GET /efaturas?filters
    C->>S: listWithFilters()
    S->>R: Dinamic Query
    R->>DB: SELECT with Filters
    DB-->>R: ResultSet
    R-->>S: Page<EFatura>
    S-->>C: Result Pageable
    C-->>UI: Model + View
    UI-->>U: Renderized List
```

### 🖥️ Technologies
- Spring MVC
- Thymeleaf
- Spring Data JPA
- PostgreSQL
