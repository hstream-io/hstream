
# HStream

High performance stream processing platform for IoT data written in Haskell.

## Architecture

```
            |----------------|
            | Stream Process |
            |----------------|
               /|\     |
                |     \|/
            |---------------|
            |  Rule | Func  |
    P ----> | Stream PubSub | ----> S
            |     Raft      |
            |---------------|
               /|\     |
                |     \|/
            |---------------|
            | Stream Store  |
            |---------------|
```

## License

Licensed under the Apache License, Version 2.0.

## Author

Feng Lee <feng@emqx.io>

