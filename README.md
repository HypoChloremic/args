# args
Python argparse cheatsheet
```
import argparse

parser = argparse.ArgumentParser()
parser.add_argument('--version', default=None, type=str, help="")
args = parser.parse_args()

```
