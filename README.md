# Acorn

Idempotent bootstrapping for seedbox

* * *

## Usage

Initial installation:

```bash
git clone https://github.com/drn/acorn.git ~/.acorn
cd ~/.acorn
~/.acorn/run
```

Regular update:

```bash
cd ~/.acorn
git fetch
git reset --hard origin/master
~/.acorn/run
```
