# Minigrep

## Case sensitive search
```
cargo run -- {word} {file}
```
Example:
```
cargo run -- to poem.txt
```

## Case insensitive search
```
IGNORE_CASE=1 cargo run -- {word} {file}
```
Example:
```
IGNORE_CASE=1 cargo run -- to poem.txt
```
