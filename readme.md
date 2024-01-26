```mermaid
graph TD
A[Start] --> B{h < 1?}
B -- Yes --> C[Print error message]
C --> D[End]
B -- No --> E{h is even?}
E -- Yes --> F[Increment h by 1]
F --> G[Initialize count to 0]
G --> H{Is i less than h?}
H -- Yes --> I{Is j less than h?}
I -- Yes --> J{Is (i >= j && i + j < h) or (i + j >= h-1 && j >= i && j != i/2)?}
J -- Yes --> K{Is (i >= j && i + j < h)?}
K -- Yes --> L{Is i less than or equal to h/2?}
L -- Yes --> M[Print i - j]
M --> N[Print space]
N --> O[Increment j by 1]
O --> I
L -- No --> P[Print h - i - j - 1]
P --> N
K -- No --> Q{Is i less than or equal to h/2?}
Q -- Yes --> R[Print abs(h - j - i - 1)]
R --> N
Q -- No --> S[Print j - i]
S --> N
J -- No --> T[Print space]
T --> O
I -- No --> U[Print new line]
U --> V[Increment i by 1]
V --> H
H -- No --> W[End]






``` 
