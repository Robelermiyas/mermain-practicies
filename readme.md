```mermaid

graph LR
A[(Start)] --> B[/Enter the number of elements n/]
B --> C[Initialize variables]
C --> D[Initialize sum, mean, variance, stdDeviation = 0]
D --> E[Initialize counter i]
E --> F{i < n}
F --> G[Enter a number ]
G --> H[Add the number to sum]
H --> I[Increment i]
I --> E[mean = sum/n]
E --> J[Calculate mean]
J --> K[Reset sum]
K --> L[Initialize counter i]
L --> M{i < n}
M --> N[Enter a number]

N --> O[variance += pow(num - mean, 2)]
O --> P[variance /= n]
P --> Q[LstdDeviation = sqrt(variance)]
L --> Q[increament i]
Q --> R[Calculate variance]
R --> S{/print variance/]
S --> T[calculate stdDevation]
T --> U[/print standard devaition/]
U --> V[(end)]
```
