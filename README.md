3PaneSublimeLayouts
===================

Key Bindings for custom 3-pane Layout in Sublime.


### Super + Alt + 6 :

![Screeshot1](/screenshots/screenshot1.png)

Add this to your Key Bindings - User file:

```
{
    "keys": ["super+alt+6"],
    "command": "set_layout",
    "args": {
        "cols": [0.0, 0.5, 1.0],
        "rows": [0.0, 0.5, 1.0],
        "cells": [
        [0, 0, 1, 2],
        [1, 0, 2, 1],
        [1, 1, 2, 2]
        ]
    }
    },

```

### Super + Alt + 7 :

![Screeshot2](/screenshots/screenshot2.png)

Add this to your Key Bindings - User file:

```
{
    "keys": ["super+alt+7"],
    "command": "set_layout",
    "args": {
        "cols": [0.0, 0.5, 1.0],
        "rows": [0.0, 0.5, 1.0],
        "cells": [
        [0, 0, 2, 1],
        [0, 1, 1, 2],
        [1, 1, 2, 2]
        ]
    }
    },
```

### Super + Alt + 8 :

![Screeshot3](/screenshots/screenshot3.png)

Add this to your Key Bindings - User file:

```
{
    "keys": ["super+alt+8"],
    "command": "set_layout",
    "args": {
        "cols": [0.0, 0.5, 1.0],
        "rows": [0.0, 0.5, 1.0],
        "cells": [
        [0, 0, 1, 1],
        [1, 0, 2, 1],
        [0, 1, 2, 2]
        ]
    }
}
```
