graph LR
    A[Reference] --> B((Sum))
    B --> C[Fuzzy-PID Controller]
    C --> D[SPIPM Model]
    D --> E[Output]
    E --> |Feedback| B
