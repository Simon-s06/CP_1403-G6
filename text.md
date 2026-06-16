```mermaid
classDiagram
    User "1" --> "*" Favourite
    Favourite "*" --> "1" Movie
    Movie "*" --> "*" Tag
    Admin --> Movie : manages
    Recommendation --> User
    Recommendation --> Movie
```
