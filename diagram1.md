sequenceDiagram
    participant Client
    participant MuleSoft API
    participant Salesforce

    Client->>MuleSoft API: Request data
    MuleSoft API->>Salesforce: Fetch data
    Salesforce-->>MuleSoft API: Data response
    MuleSoft API-->>Client: Provide data