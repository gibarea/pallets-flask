classDiagram
    class User {
        +int id
        +String username
        +String password
    }
    class Post {
        +int id
        +int author_id
        +Time created
        +String tittle
        +String body
    }
    User "1" --> "*" Post : author_id
