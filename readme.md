'''mermaid
graph TD
    A[Start] --> B[Input n]
    B --> C[Initialize sum, sumSquared, and count]
    C --> D[Input x]
    D --> E[Add x to sum]
    E --> F[Add x^2 to sumSquared]
    F --> G[Increment count]
    G --> H[Check if count < n]
    H -- Yes --> D
    H -- No --> I[Calculate mean]
    I --> J[Calculate variance]
    J --> K[Calculate standard deviation]
    K --> L[Output mean, variance, and standard deviation]
    L --> M[Stop]
'''
