```mermaid

graph LR
A[(Start)] --> B[/Enter the number of elements/]
B --> C[Initialize variables]
C --> D[Initialize sum, mean, variance, stdDeviation]
D --> E[Initialize counter i]
E --> F{i < n}
F --> G[Enter a number]
G --> H[Add the number to sum]
H --> I[Increment i]
I --> E[mean = sum/n]
E --> J[Calculate mean]
J --> K[Reset sum]
K --> L[Initialize counter i]
L --> M{i < n}
M --> N[Enter a number]

N --> O[variance = (sumSquared / n) - (mean * mean)]
O --> P[calculate variance]
P --> L[increament i]
L --> Q[Calculate average variance]
Q --> R[Calculate standard deviation]
R --> S{/print variance/]
S --> T[/print standard devaition/]
T --> U[(End)]

```
