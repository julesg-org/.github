# julesg-org

Welcome to the **julesg-org** GitHub organisation — a home for curious minds and creative code.

---

## Euler's Identity

Perhaps the most beautiful equation in mathematics:

$$e^{i\pi} + 1 = 0$$

It unites five fundamental constants — $e$, $i$, $\pi$, $1$, and $0$ — in a single, breathtaking expression.

---

## Fibonacci via Recursion (C)

```c
#include <stdio.h>

/* O(2^n) — elegant for illustration; use memoisation for large n */
int fibonacci(int n) {
    if (n <= 0) return 0;
    if (n == 1) return 1;
    return fibonacci(n - 1) + fibonacci(n - 2);
}

int main(void) {
    int terms = 10;
    for (int i = 0; i < terms; i++) {
        printf("F(%d) = %d\n", i, fibonacci(i));
    }
    return 0;
}
```

---

## A Poem About Melbourne

**City of the South**

Where the Yarra bends and trams glide slow,
Through laneways dressed in street-art glow,
A city stitched from coffee steam
And architects' half-finished dream.

The footy roars on winter days,
The MCG ablaze with praise,
While Luna Park grins wide and bright
Beneath the harbour's amber light.

In autumn, plane trees line the street
With gold and rust beneath your feet,
And when the weather can't decide,
Four seasons come in one day's ride.

So here's to Melbourne — bold and free,
A southern soul beside the sea,
Where culture blooms and stories grow,
In this great city's endless show.

---

*"The important thing is not to stop questioning." — Albert Einstein*
