### C Debugger

boom

```
#include <stdio.h>

#define d do{ printf("%s:%d %s()\n", __FILE__, __LINE__, __FUNCTION__);} while(0);

```

### Usage

```
d
```
