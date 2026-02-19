```c
#include <stdio.h>

int main() {
  const int minutesPerHour = 60;
  const int monthsInYear = 12;

  printf("%d\n", minutesPerHour);
  printf("%d\n", monthsInYear);
  return 0;
}

```
---

`You have already seen the break statement used in an earlier chapter of this tutorial. It was used to "jump out" of a switch statement.`

`The break statement can also be used to jump out of a loop.`

`This example stops the loop when i is equal to 4`
```c
int i;

for (i = 0; i < 10; i++) {
  if (i == 4) {
    break;
  }
  printf("%d\n", i);
}
```
