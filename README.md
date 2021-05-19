# rime-ayaka-2021

rime input schema for Ayaka’s Romanization of Middle Chinese (2021 Version)

Based on [ayaka14732/rime-kyonh](https://github.com/ayaka14732/rime-kyonh)

## Build

```sh
mkdir -p cache
node build/generate_map.js
python build/build.py
python build/build_unspaced.py
```
