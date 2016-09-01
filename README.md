# tlv-parser
[![Build Status](https://travis-ci.org/lexxvir/tlv-parser.svg?branch=master)](https://travis-ci.org/lexxvir/tlv-parser.svg)
[![Latest Version](https://img.shields.io/crates/v/tlv_parser.svg)](https://crates.io/crates/tlv_parser)
![Docs](https://docs.rs/tlv_parser/badge.svg)

Library for parsing BER-TLV

[Documentation](https://lexxvir.github.io/tlv-parser/tlv_parser/index.html)

Library is early development stage and supports parsing from `Vec<u8>` and emitting `Vec<u8>`.

*For now, it only builds on nightly.*

For usage see [`examples/print.rs`](https://github.com/lexxvir/tlv-parser/blob/master/examples/print.rs).

```
$ echo "7003820151" | cargo run --example print
     Running `target/debug/examples/print`
	 tag=70
	   tag=82,     len=1,    data=51 Q
```

