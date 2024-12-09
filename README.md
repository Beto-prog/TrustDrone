# In God (and Rust) We Trust
Welcome to the repository of the drone "In God (and Rust) We Trust".

Team members:
- Alberto Rovesti (the Mighty Leader)
- Mattia Ferretti
- Lorenzo Cortese
- Dumitru-Robert Blaga

# User guide
In order to use our implementation of the drone you need to follow these steps:
1. Add our repo link in your `Cargo.toml` file under the `[dependencies]` section. It should look something like this:
```rust
[dependencies]
TrustDrone = { git = "https://github.com/Beto-prog/TrustDone", package = "drone" }
```
2. Update cargo
   
```bash
cargo clean
cargo update
cargo build
```

3. After that you can use our amazing drone in your network initializer like this:

```rust
use TrustDrone::TrustDrone as TrsDrone;

```

4. Pray God (or Rust, or both) it works
5. If the previous step didn't work, feel free to write us on this Telegram group
```
https://t.me/+HDoQkiV2qK0zZjc0
```

 
