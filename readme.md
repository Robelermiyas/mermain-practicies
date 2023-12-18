```mermaid

graph LR
A[Start] --> B[/Enter the number of elements/]
B --> C[Initialize variables]
C --> D[sum, mean, variance, stdDeviation = 0]
D --> E[Initialize counter i]
E --> F{Loop until i < n}
F --> G[Enter a number]
G --> H[Add the number to sum]
H --> I[Increment i]
I --> E
E --> J[/Calculate mean/]
J --> K[Reset sum]
K --> L[Initialize counter i]
L --> M[Loop until i < n]
M --> N[Enter a number]
N --> O[/Calculate variance/]
O --> P[Increment i]
P --> L
L --> Q/Calculate average varianc/e]
Q --> R[/Calculate standard deviation/]
R --> S[Output input numbers]
S --> T[Output mean and standard deviation]
T --> U[End]
```
