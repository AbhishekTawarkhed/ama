erDiagram
    USERS {
        int user_id PK
        string username
        string email
    }
    POSTS {
        int post_id PK
        string content
        int user_id FK
    }
    COMMENTS {
        int comment_id PK
        string content
        int user_id FK
        int post_id FK
        int parent_comment_id FK
    }
    LIKES {
        int like_id PK
        int user_id FK
        int post_id FK
    }
    FOLLOWS {
        int follower_id FK
        int following_id FK
    }

    USERS ||--o{ POSTS : "creates"
    USERS ||--o{ COMMENTS : "writes"
    POSTS ||--o{ COMMENTS : "has"
    COMMENTS ||--o{ COMMENTS : "threads"
    USERS ||--o{ LIKES : "gives"
    POSTS ||--o{ LIKES : "receives"
    USERS ||--o{ FOLLOWS : "follows"
