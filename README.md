# isolanguage-1


#### With additional modifications to support converting three-letter codes like `eng` or `ger`.

___

This crate implements the [ISO 639-1](https://en.wikipedia.org/wiki/ISO_639-1) standard in Rust.
It also has optional Serde support, by using the `serde` feature:

```toml
isolanguage-1 = { version = "0.2.3", git = "https://github.com/Vernoxvernax/isolanguage-1" , features = ["serde"] }
```

The main type is the `LanguageCode` type, which is an enum for every single language in ISO
639-1. It optionally implements Serialize and Deserialize too.

License: MIT OR Apache-2.0
