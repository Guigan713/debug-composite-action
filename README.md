# debug-composite-action

Simple GitHub action to debug our workflow

## usage

```yaml
on: 
    push:

jobs:
    test:
        runs-on: ubuntu-latest
        name: just test debug action
        steps:
            - uses: Guigan713/debug-composite-action@main
```